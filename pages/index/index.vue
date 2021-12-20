<template>
	<view class="content">
		<!-- <image class="logo" src="/static/logo.png"></image> -->
		<view class="text-area">
			<view class="title">{{title}}</view>
			<expandable-text :line="2" :expandText="'展展'" :foldText="'收收'" :longText="content">
			</expandable-text>
			<view style="height: 20px;"></view>
			<expandable-text :line="2" :expandText="'展展'" :foldText="'收收'">
				浮动元素是如何定位的正如我们前面提到的那样，当一个元素浮动之后，它会被移出正常的文档流，然后向左或者向右平移，一直平移直到碰到了所处的容器的边框，或者碰到另外一个浮动的元素。
			</expandable-text>
			<view style="height: 20px;"></view>
			<expandable-text :line="3" :expandText="'展展'" :foldText="'收收'">
				浮动元素是如何定位的正如我们前面，浮动元素是如何定位的正如我们前面
			</expandable-text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Expandable Text',
				content: `浮动元素是如何定位的
				正如我们前面提到的那样，当一个元素浮动之后，它会被移出正常的文档流，然后向左或者向右平移，一直平移直到碰到了所处的容器的边框，或者碰到另外一个浮动的元素。
				浮动元素是如何定位的
				正如我们前面提到的那样，当一个元素浮动之后，它会被移出正常的文档流，然后向左或者向右平移，一直平移直到碰到了所处的容器的边框，或者碰到另外一个浮动的元素。
				浮动元素是如何定位的
				正如我们前面提到的那样，当一个元素浮动之后，它会被移出正常的文档流，然后向左或者向右平移，一直平移直到碰到了所处的容器的边框，或者碰到另外一个浮动的元素。
				浮动元素是如何定位的
				正如我们前面提到的那样，当一个元素浮动之后，它会被移出正常的文档流，然后向左或者向右平移，一直平移直到碰到了所处的容器的边框，或者碰到另外一个浮动的元素。
				浮动元素是如何定位的
				正如我们前面提到的那样，当一个元素浮动之后，它会被移出正常的文档流，然后向左或者向右平移，一直平移直到碰到了所处的容器的边框，或者碰到另外一个浮动的元素。
				浮动元素是如何定位的
				正如我们前面提到的那样，当一个元素浮动之后，它会被移出正常的文档流，然后向左或者向右平移，一直平移直到碰到了所处的容器的边框，或者碰。`
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		width: 100vw;
		box-sizing: border-box;
		/* display: flex; */
		/* justify-content: center; */
		padding: 24rpx;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
