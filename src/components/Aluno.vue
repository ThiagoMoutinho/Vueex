<template>
    <div>
        <p>Aluno {{ aulasCompletas }}</p>
    </div>
</template>



<script>
import { mapState } from 'vuex';
export default {
    name: "AlunoVue",
    computed: {
        ...mapState([
            "aulasCompletas"
        ])
    }
    
}
</script>