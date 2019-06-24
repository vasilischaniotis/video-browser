<template>
    <div>
        <SearchBar @termChange="onTermChange"></SearchBar>
    </div>
</template>

<script>
import SearchBar from './components/SearchBar';
const API_KEY = 'AIzaSyBskXTwgcYG5yKcX1Uwrv9K1uc8nb16jYU';

export default {
    name: 'App',
    components: {
        SearchBar
    },
    methods: {
        onTermChange(searchTerm) {
            console.log(searchTerm);
        }
    }
};
</script>
