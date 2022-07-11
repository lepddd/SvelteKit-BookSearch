<script>
    import Icon from '@iconify/svelte';    
</script>

<footer>
    <span class="title">BookSearch</span>
    <span class="copyright">Copyright 2020 Luiz Dornelas All rights reserved</span>
    <ul>
        <li><a href="https://github.com/lepddd"><Icon class="github-icon" icon="akar-icons:github-fill" /></a></li>
    </ul>
</footer>

<style>
    footer{
        display: flex;
        align-items: center;
        justify-content: space-between;
        background-color: #CED4DA;
        padding: 25px 100px;
    }
    .title{
        color: #EF233C;
        font-size: 48px;
        font-family: Asiyah Script;
    }
    .copyright{
        font-family: Typo Grotesk;
        color: #495057;
        font-size: 16px;
        font-weight: 700;
    }
    ul{
        list-style: none;
    }
    ul li a{
        text-decoration: none;
        color: #495057;
    }
    :global(.github-icon){
        width: 24px;
        height: 24px;        
    }    
</style>