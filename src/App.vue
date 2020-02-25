<template>
    <div class="main">
        <name></name>
        <education></education>
        <skill></skill>
        <project></project>
        <honour></honour>
        
    </div>
</template>

<script>
import Name from "./components/Name";
import Education from "./components/Education";
import Skill from "./components/Skill";
import Project from './components/Project';
import Honour from './components/Honour';

export default {
    components: {
        Name,
        Education,
        Skill,
        Project,
        Honour
    }
};
</script>

<style lang='stylus' scoped>
.main
  width 800px
</style>

