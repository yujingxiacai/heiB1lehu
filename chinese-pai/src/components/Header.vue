<template>
    <header id="fh5co-header" role="banner">
		<div class="container">
			<div class="row">
        		<div class="col-md-6">
            			<button class="btn btn-primary">测试按钮</button>
        		</div>
    		</div>
			<div class="header-inner">
				<!-- 主页定向 -->
				<a class="navbar-brand" href="index.html">
					<img src="images/logo.png" alt="logo">
				</a>
				<nav role="navigation">
					<ul>
						<!-- 菜单跳转1 -->
						<li><a href="index.html">一对一</a></li>
						<!-- 菜单跳转2 -->
						<li><a href="be-teacher.html">我要当教师</a></li>
						<!-- 菜单跳转3 -->
						<li><a href="public-class.html">公开课</a></li>
						<li class="dropdown">
							<a class="dropdown-toggle" data-toggle="dropdown" href="#">
								课程<span class="caret"></span>
							</a>
							<ul class="dropdown-menu">
								<!-- 菜单跳转4 -->
								<li><a href="course-free.html" style="color:black;">免费课程</a></li>
							</ul>
						</li>
						<!-- 菜单跳转5 -->
						<li><a href="community.html">社区</a></li>
						<li class="cta"><button type="button" class="btn btn-primary btn-right" data-toggle="modal" data-target="#myModal">登录/注册</button></li>
					</ul>
				</nav>
			</div>
		</div>
	</header>
</template>

<script>
import 'bootstrap';
export default {
    
}
</script>

<style lang="sass" scoped>

</style>
