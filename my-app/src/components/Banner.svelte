<script>
	import Icon from '@iconify/svelte';
</script>

<div class="container">
    <div class="banner">
        <p class="title__1">Find the <span>books</span> you love and discovery more about</p>
        <p class="title__2">
            Track the books by name, author or the publisher, it's simple, just type and search
        </p>
        <a href="/search">Search now<Icon class="arrow-icon" icon="carbon:arrow-right" /></a>
    </div>
    <img src="./storyset.svg" alt="" srcset="">
</div>

<style>
    .container{
        display: flex;
        justify-content: center;
        align-items: center;
    }
	.banner {
		font-family: Typo Grotesk;
        width: 337px;
        height: 400px;
        padding: 62px 20px;
        background-color: #EDF6F9;
        margin-right: 20px;
	}
	.title__1 {
		font-size: 32px;
        margin-bottom: 20px;
		color: #495057;
	}
	.title__1 span {
		color: #ef233c;
	}
	.title__2 {
		font-size: 16px;
        margin-bottom: 30px;
		color: #495057;
	}
	a {
        display: flex;
        align-items: center;
        justify-content: center;
		width: 100%;
		height: 50px;
		background-color: #ef233c;
		border: none;
        border-radius: 5px;
        color: #EDF6F9;
        font-size: 16px;
        font-weight: 700;
        text-decoration: none;
	}
    a :global(.arrow-icon){
        width: 19px;
        height: 19px;
        margin-left: 10px;        
    }
</style>
