<template>
    <div>
        <section>
            <base-card>
                <h2>Coach Rgistration</h2>
                <coach-form></coach-form>
            </base-card>
        </section>
    </div>
</template>

<script>
import CoachForm from '../../components/coaches/CoachForm.vue';

export default {
    components: {
        CoachForm
    }
};
</script>
