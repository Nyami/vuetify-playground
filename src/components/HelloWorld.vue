<template>
    <v-container>
        <v-layout text-center wrap>
            <v-flex xs12>
                <v-menu offset-y>
                    <template v-slot:activator="{ on }">
                        <v-btn fab color="primary" outlined small v-on="on">
                            <v-icon>mdi-mouse</v-icon>
                        </v-btn>
                    </template>
                    <v-list dense>
                        <v-list-item>
                            <v-list-item-title>One</v-list-item-title>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-title>Two</v-list-item-title>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-title>Three</v-list-item-title>
                        </v-list-item>
                    </v-list>
                </v-menu>
            </v-flex>
        </v-layout>
    </v-container>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
    data: () => ({}),
});
</script>
