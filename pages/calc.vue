<template>
    <div>
        <h1 class="title">
            {{mensagem}}
        </h1>
        <b-button type="is-primary" @click="teste()">
            Clique aqui
        </b-button>
        
        <b-field label="mensagem">
            <b-input v-model="mensagem"></b-input>
        </b-field>

        <hr>

        <b-button type="is-primary" @click="soma()">
            +
        </b-button>
        <b-button type="is-primary" @click="subtraçao()">
            -
        </b-button>
        <b-button type="is-primary" @click="multi()">
            *
        </b-button>
        <b-button type="is-primary" @click="div()">
            /
        </b-button>

        <b-field label="Primeiro número">
            <b-input v-model="numero1"></b-input>
        </b-field>

        <b-field label="Segundo número">
            <b-input v-model="numero2"></b-input>
        </b-field>

        <b-field label="Resultado">
            <b-input v-model="resultado"></b-input>
        </b-field>


    </div>
</template>

<script>
    export default {
        data( ) {
            return{
                mensagem: "olá mundo",
                numero1: 0,
                numero2: 0,
                resultado: 0
            }
        },
        methods: {
            teste() {
                this.mensagem = "Nova mensagem";

            },
            soma(){
                this.resultado =  parseInt(this.numero1) + parseInt( this.numero2);
            },
            subtraçao(){
                this.resultado =  parseInt(this.numero1) - parseInt( this.numero2);
            },
            multi(){
                this.resultado =  parseInt(this.numero1) * parseInt( this.numero2);
            },
            div(){
                this.resultado =  parseInt(this.numero1) / parseInt( this.numero2);
            },


        }
    }
</script>