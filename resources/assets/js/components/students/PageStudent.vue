<template>
    <div class="page-student">
        <section>
            <div class="container-fluid bg-primary text-light pt-5">
                <div class="page-title text-center">
                    <h3>My Courses</h3>
                    <nav class="nav text-light justify-content-center">
                        <a
                            class="nav-link active"
                            href="#"
                        >My Courses</a>
                        <a
                            class="nav-link"
                            href="#"
                        >My Exams</a>
                        <a
                            class="nav-link"
                            href="#"
                        >Certifications</a>
                    </nav>
                </div>
            </div>
        </section>
        <RouterView />
    </div>
</template>

<script>
import routs from './routs'
export default {
    data () {
        return {

        }
    },
    computed: {

    },
    created () {
        this.$router.addRoutes(routs)
    },
    methods: {

    }
}
</script>
