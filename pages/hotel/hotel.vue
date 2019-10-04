<template>
	<view class="content">
		<view class="hotel-top">
			<img width="100%" height="100%" src="../../static/icon/酒店/酒店详细页/top.jpg" mode=""></img>
			<view class="hotel-top-menu">
				<a href="javascript:0;">
					<img width="100%" height="100%" src="../../static/icon/酒店/酒店详细页/返 回.png" alt="">
				</a>
				<a href="javascript:0;">
					<img width="100%" height="100%" src="../../static/icon/酒店/酒店详细页/返 回.png" alt="">
				</a>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.content{
		background: #F8F8F8;
	}
	.hotel-top{
		height: 418upx;
	}
	.hotel-top-menu{
		position: absolute;
		top: 0;
		left: 0;
		display: flex;
		justify-content: space-between;
		align-content: center;
	}
	.hotel-top-menu a{
		display: block;
		width: 40upx;
		height: 40upx;
	}
</style>
