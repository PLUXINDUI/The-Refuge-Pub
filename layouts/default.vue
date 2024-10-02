<template> 
    <Header />
    <nuxt :key="$route.fullPath" />
</template>

<script>
import { Header } from 'components/header/header';

export default{
    comments: {
       Header 
    }
}
</script>