<template>
	<div>
		<div class="container">
			<div class="side-bar">
				<router-link to="/task01">啦啦啦</router-link>
				<router-link to="/task02">啦啦啦</router-link>
				<router-link to="/task03">啦啦啦</router-link>
			</div>
			<div class="content"><router-view /></div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Task',
	data(){
		return {
			
		};
	}
};
</script>

<style scoped>
	.container{
		display: flex;
		
		width: 80%;
		margin: 0 auto;
		
	}
	.side-bar{
		flex: 1 1 20%;
		display: flex;
		flex-direction: column;
		background-color: #fff;
		margin-top: 20px;
	}
	a{
		margin-bottom: 30px;
	}
	.content{
		flex: 1 1 80%;
		text-align: left;
		background-color: #fff;
		margin-left: 20px;
		padding-bottom: 20px;
	}
</style>
