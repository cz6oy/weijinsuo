<template>
  <div class="hello">
    <!-- 头部区域 -->
    <header class="header">
      <div class="topBar visible-md visible-lg">
        <div class="container">
          <div class="row">
            <div class="col-md-2 text-center">
              <a href="#" class="mobile-link">
                <i class="icon-mobilephone"></i>
                <span>手机微金所</span>
                <i class="glyphicon glyphicon-chevron-down"></i>
                <img src="../assets/c_06.jpg" height="136" width="120" alt="扫一扫">
              </a>
            </div>
            <div class="col-md-5 text-center">
              <i class="icon-telephone"></i>
              <span>4006-89-4006（服务时间：9:00-21:00）</span>
            </div>
            <div class="col-md-2 text-center">
              <a href="#">常见问题</a>
              <a href="#">财富登录</a>
            </div>
            <div class="col-md-3 text-center">
              <a href="#" class="btn-itcast btn btn-danger btn-sm">免费注册</a>
              <a href="#" class="btn btn-link btn-sm" data-toggle="modal" data-target="#myModal">登录</a>
            </div>
          </div>
        </div>
      </div>
      <nav class="navbar navbar-itcast navbar-static-top" data-spy="affix" data-offset-top="60" data-offset-bottom="200">
        <div class="container">
          <div class="navbar-header">
            <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
              <span class="sr-only">切换菜单</span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
            </button>
            <a class="navbar-brand" href="#">
              <i class="icon-icon"></i>
              <i class="icon-logo"></i>
            </a>
          </div>
          <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
            <ul class="nav navbar-nav">
              <li class="active"><a href="#">我要投资</a></li>
              <li><a href="#">我要投资</a></li>
              <li><a href="#">我要投资</a></li>
              <li><a href="#">我要投资</a></li>
              <li><a href="#">我要投资</a></li>
              <li><a href="#">我要投资</a></li>
            </ul>
            <ul class="nav navbar-nav navbar-right hidden-sm">
              <li><a href="#">个人中心</a></li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <!-- 广告轮播图 -->
    <section class="main_ad">
      <div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
        <!-- 轮播指示器，小点点 -->
        <ol class="carousel-indicators">
          <li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
          <li data-target="#carousel-example-generic" data-slide-to="1"></li>
          <li data-target="#carousel-example-generic" data-slide-to="2"></li>
        </ol>
        <!-- 轮播内容 -->
        <div class="carousel-inner" role="listbox">
          <div class="item active">
            <img :src="bgImgJudge(0)" alt="">
            <div class="carousel-caption">
              标题1
            </div>
          </div>
          <div class="item">
            <img :src="bgImgJudge(1)" alt="">
            <div class="carousel-caption">
              标题2
            </div>
          </div>
          <div class="item">
            <img :src="bgImgJudge(2)" alt="">
            <div class="carousel-caption">
              标题3
            </div>
          </div>
        </div>
        <!-- 控制按钮 -->
        <a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
          <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
          <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
    </section>
    <!-- 特色介绍 -->
    <section class="main_tese hidden-xs">
      <div class="container">
        <div class="row">
          <div class="col-sm-6 col-md-4">
            <div class="media">
              <a href="#">
                <div class="media-left">
                  <i class="icon-uniE907"></i>
                </div>
                <div class="media-body">
                  <h4 class="media-heading">支付交易保障</h4>
                    银联支付全称保证支付安全
                </div>
              </a>
            </div>
          </div>
          <div class="col-sm-6 col-md-4">
            <div class="media">
              <a href="#">
                <div class="media-left">
                  <i class="icon-uniE907"></i>
                </div>
                <div class="media-body">
                  <h4 class="media-heading">支付交易保障</h4>
                    银联支付全称保证支付安全
                </div>
              </a>
            </div>
          </div>
          <div class="col-sm-6 col-md-4">
            <div class="media">
              <a href="#">
                <div class="media-left">
                  <i class="icon-uniE907"></i>
                </div>
                <div class="media-body">
                  <h4 class="media-heading">支付交易保障</h4>
                    银联支付全称保证支付安全
                </div>
              </a>
            </div>
          </div>
          <div class="col-sm-6 col-md-4">
            <div class="media">
              <a href="#">
                <div class="media-left">
                  <i class="icon-uniE907"></i>
                </div>
                <div class="media-body">
                  <h4 class="media-heading">支付交易保障</h4>
                    银联支付全称保证支付安全
                </div>
              </a>
            </div>
          </div>
          <div class="col-sm-6 col-md-4">
            <div class="media">
             <a href="#">
                <div class="media-left">
                  <i class="icon-uniE907"></i>
                </div>
                <div class="media-body">
                  <h4 class="media-heading">支付交易保障</h4>
                    银联支付全称保证支付安全
                </div>
              </a>
            </div>
          </div>
          <div class="col-sm-6 col-md-4">
            <div class="media">
              <a href="#">
                <div class="media-left">
                  <i class="icon-uniE907"></i>
                </div>
                <div class="media-body">
                  <h4 class="media-heading">支付交易保障</h4>
                    银联支付全称保证支付安全
                </div>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- 立即预约 -->
    <section class="main_ljyy">
      <div class="container">
        <p class="pull-left">
          <i class="icon-uniE906"></i>现在有<span>458</span>人在排队，累计预约交易成功<span>7409</span>次。 什么是预约投标？ <a href="#">立即预约</a>
        </p>
        <p class="pull-right hidden-sm hidden-xs">
          <i class="icon-uniE905"></i><a href="#">微金所企业宣传片</a>
        </p>
      </div>
    </section>
    <!-- 产品推荐 -->
    <section class="main_prod">
      <div class="container">
        <div class="ul-wapper">
          <!-- 选项卡标题 -->
          <ul class="nav nav-tabs" role="tablist">
            <li role="presentation" class="active"><a href="#home" aria-controls="home" role="tab" data-toggle="tab">特别推荐</a></li>
            <li role="presentation"><a href="#profile" aria-controls="profile" role="tab" data-toggle="tab">微投资</a></li>
            <li role="presentation"><a href="#messages" aria-controls="messages" role="tab" data-toggle="tab">微小宝</a></li>
            <li role="presentation"><a href="#settings" aria-controls="settings" role="tab" data-toggle="tab">微消费</a></li>
            <li role="presentation"><a href="#settings" aria-controls="settings" role="tab" data-toggle="tab">微增利</a></li>
            <li role="presentation"><a href="#settings" aria-controls="settings" role="tab" data-toggle="tab">微金宝</a></li>
            <li role="presentation"><a href="#settings" aria-controls="settings" role="tab" data-toggle="tab">微转让</a></li>
            <li class="pull-right hidden-sm hidden-xs"><a href="#">更多</a></li>
          </ul>
        </div>
          <!-- 选项卡内容 -->
        <div class="tab-content">
            <div role="tabpanel" class="tab-pane fade in active" id="home">
              <div class="row">
                <div class="col-xs-12 col-sm-6 col-md-4">
                  <div class="panel panel-czbk active">
                    <div class="panel-heading">
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-xs-12 col-sm-6 col-md-4">
                  <div class="panel panel-czbk disabled">
                    <div class="panel-heading">
                      <p class="tooltips">
                        <a class="badge badge-one" style="color:#e92322;" data-toggle="tooltip" data-placement="top" title="北京欢迎你" href="#">京</a>
                        <a class="badge badge-two" style="color:#337ab7;" data-toggle="tooltip" data-placement="top" title="上海欢迎你" href="#">沪</a>
                      </p>
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-xs-12 col-sm-6 col-md-4">
                  <div class="panel panel-czbk disabled">
                    <div class="panel-heading">
                      <p class="tooltips">
                        <a class="badge badge-one" style="color:#e92322;" data-toggle="tooltip" data-placement="top" title="北京欢迎你" href="#">京</a>
                        <a class="badge badge-two" style="color:#337ab7;" data-toggle="tooltip" data-placement="top" title="上海欢迎你" href="#">沪</a>
                      </p>
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-xs-12 col-sm-6 col-md-4">
                  <div class="panel panel-czbk disabled">
                    <div class="panel-heading">
                      <p class="tooltips">
                        <a class="badge badge-one" style="color:#e92322;" data-toggle="tooltip" data-placement="top" title="北京欢迎你" href="#">京</a>
                        <a class="badge badge-two" style="color:#337ab7;" data-toggle="tooltip" data-placement="top" title="上海欢迎你" href="#">沪</a>
                      </p>
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-xs-12 col-sm-6 col-md-4">
                  <div class="panel panel-czbk disabled">
                    <div class="panel-heading">
                      <p class="tooltips">
                        <a class="badge badge-one" style="color:#e92322;" data-toggle="tooltip" data-placement="top" title="北京欢迎你" href="#">京</a>
                        <a class="badge badge-two" style="color:#337ab7;" data-toggle="tooltip" data-placement="top" title="上海欢迎你" href="#">沪</a>
                      </p>
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-xs-12 col-sm-6 col-md-4">
                  <div class="panel panel-czbk disabled">
                    <div class="panel-heading">
                      <p class="tooltips">
                        <a class="badge badge-one" style="color:#e92322;" data-toggle="tooltip" data-placement="top" title="北京欢迎你" href="#">京</a>
                        <a class="badge badge-two" style="color:#337ab7;" data-toggle="tooltip" data-placement="top" title="上海欢迎你" href="#">沪</a>
                      </p>
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-xs-12 col-sm-6 col-md-4">
                  <div class="panel panel-czbk disabled">
                    <div class="panel-heading">
                      <p class="tooltips">
                        <a class="badge badge-one" style="color:#e92322;" data-toggle="tooltip" data-placement="top" title="北京欢迎你" href="#">京</a>
                        <a class="badge badge-two" style="color:#337ab7;" data-toggle="tooltip" data-placement="top" title="上海欢迎你" href="#">沪</a>
                      </p>
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-xs-12 col-sm-6 col-md-4">
                  <div class="panel panel-czbk disabled">
                    <div class="panel-heading">
                      <p class="tooltips">
                        <a class="badge badge-one" style="color:#e92322;" data-toggle="tooltip" data-placement="top" title="北京欢迎你" href="#">京</a>
                        <a class="badge badge-two" style="color:#337ab7;" data-toggle="tooltip" data-placement="top" title="上海欢迎你" href="#">沪</a>
                      </p>
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div role="tabpanel" class="tab-pane fade" id="profile">
               <div class="row">
                <div class="col-xs-12 col-sm-6 col-md-4">
                  <div class="panel panel-czbk active">
                    <div class="panel-heading">
                      <p class="tooltips">
                        <a class="badge badge-one" style="color:#e92322;" data-toggle="tooltip" data-placement="top" title="北京欢迎你" href="#">京</a>
                        <a class="badge badge-two" style="color:#337ab7;" data-toggle="tooltip" data-placement="top" title="上海欢迎你" href="#">沪</a>
                      </p>
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="panel panel-czbk disabled">
                    <div class="panel-heading">
                      <p class="tooltips">
                        <a class="badge badge-one" style="color:#e92322;" data-toggle="tooltip" data-placement="top" title="北京欢迎你" href="#">京</a>
                        <a class="badge badge-two" style="color:#337ab7;" data-toggle="tooltip" data-placement="top" title="上海欢迎你" href="#">沪</a>
                      </p>
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                       <div class="panel panel-czbk disabled">
                    <div class="panel-heading">
                      <p class="tooltips">
                        <a class="badge badge-one" style="color:#e92322;" data-toggle="tooltip" data-placement="top" title="北京欢迎你" href="#">京</a>
                        <a class="badge badge-two" style="color:#337ab7;" data-toggle="tooltip" data-placement="top" title="上海欢迎你" href="#">沪</a>
                      </p>
                      <p><strong>8</strong><sub>%</sub></p>
                      <p><span>年利率</span></p>
                    </div>
                    <div class="panel-body">
                      <h4>新手体验表0008期</h4>
                      <div class="row">
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-left">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                        <div class="col-xs-6 text-right">
                          <p>起步价</p>
                          <p><strong>1000.00</strong><sub>万</sub></p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div role="tabpanel" class="tab-pane fade" id="messages">ssssssssssssssssssssssssssssssssss</div>
            <div role="tabpanel" class="tab-pane fade" id="settings">ssssssssssssssssssssssssssssssssss</div>
            <div role="tabpanel" class="tab-pane fade" id="settings">ssssssssssssssssssssssssssssssssss</div>
            <div role="tabpanel" class="tab-pane fade" id="settings">ssssssssssssssssssssssssssssssssss</div>
            <div role="tabpanel" class="tab-pane fade" id="settings">ssssssssssssssssssssssssssssssssss</div>
          </div>
      </div>
    </section>
    <!-- 新闻列表 -->
    <section class="main_news">
      <div class="container">
        <div class="row">
          <div class="col-sm-2 col-sm-offset-3">
            <div class="news-title">
              {{newsTitle}}
            </div>
          </div>
          <div class="col-sm-1">
            <ul class="nav nav-pills nav-stacked text-center">
              <li role="presentation" class="active"><a href="#news01" data-toggle="tab" role="tab" @click="clickBtn(0)"><i class="icon-news01"></i></a></li>
              <li role="presentation"><a href="#news02" data-toggle="tab" role="tab" @click="clickBtn(1)"><i class="icon-news01"></i></a></li>
              <li role="presentation"><a href="#news03" data-toggle="tab" role="tab" @click="clickBtn(2)"><i class="icon-news01"></i></a></li>
              <li role="presentation"><a href="#news04" data-toggle="tab" role="tab" @click="clickBtn(3)"><i class="icon-news01"></i></a></li>
            </ul>
          </div>
          <div class="col-sm-6">
            <div class="tab-content">
              <div role="tabpanel" class="tab-pane in active" id="news01">
                <ul>
                  <li>微金所发钱了，快来抢！！！</li>
                  <li>微金所发钱了，快来抢！！！</li>
                  <li>微金所发钱了，快来抢！！！</li>
                  <li>微金所发钱了，快来抢！！！</li>
                  <li>微金所发钱了，快来抢！！！</li>
                  <li>微金所发钱了，快来抢！！！</li>
                  <li>微金所发钱了，快来抢！！！</li>
                  <li>微金所发钱了，快来抢！！！</li>
                  <li>微金所发钱了，快来抢！！！</li>
                  <li>微金所发钱了，快来抢！！！</li>
                </ul>
              </div>
              <div role="tabpanel" class="tab-pane" id="news02">
                <ul>
                  <li>1111111111111111111111111</li>
                  <li>1111111111111111111111111</li>
                  <li>1111111111111111111111111</li>
                  <li>1111111111111111111111111</li>
                  <li>1111111111111111111111111</li>
                  <li>1111111111111111111111111</li>
                  <li>1111111111111111111111111</li>
                  <li>1111111111111111111111111</li>
                  <li>1111111111111111111111111</li>
                  <li>1111111111111111111111111</li>
                  <li>1111111111111111111111111</li>
                </ul>
              </div>
              <div role="tabpanel" class="tab-pane" id="news03">
                <ul>
                  <li>2222222222222222222222222222</li>
                  <li>2222222222222222222222222222</li>
                  <li>2222222222222222222222222222</li>
                  <li>2222222222222222222222222222</li>
                  <li>2222222222222222222222222222</li>
                  <li>2222222222222222222222222222</li>
                  <li>2222222222222222222222222222</li>
                  <li>2222222222222222222222222222</li>
                  <li>2222222222222222222222222222</li>
                  <li>2222222222222222222222222222</li>
                </ul>
              </div>
              <div role="tabpanel" class="tab-pane" id="news04">
                <ul>
                  <li>3333333333333333333333333333333333</li>
                  <li>3333333333333333333333333333333333</li>
                  <li>3333333333333333333333333333333333</li>
                  <li>3333333333333333333333333333333333</li>
                  <li>3333333333333333333333333333333333</li>
                  <li>3333333333333333333333333333333333</li>
                  <li>3333333333333333333333333333333333</li>
                  <li>3333333333333333333333333333333333</li>
                  <li>3333333333333333333333333333333333</li>
                  <li>3333333333333333333333333333333333</li>
                  <li>3333333333333333333333333333333333</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="main_hzhb center-block hidden-sm hidden-xs">
      <div class="container text-center">
        <h3>合作伙伴</h3>
        <ul class="center-block">
          <li><a href="#"><i class="icon-uniE930"></i></a></li>
          <li><a href="#"><i class="icon-uniE92F"></i></a></li>
          <li><a href="#"><i class="icon-uniE92E"></i></a></li>
          <li><a href="#"><i class="icon-uniE92A"></i></a></li>
          <li><a href="#"><i class="icon-uniE929"></i></a></li>
          <li><a href="#"><i class="icon-uniE931"></i></a></li>
          <li><a href="#"><i class="icon-uniE92C"></i></a></li>
          <li><a href="#"><i class="icon-uniE92B"></i></a></li>
          <li><a href="#"><i class="icon-uniE92D"></i></a></li>
        </ul>
      </div>
    </section>  
    <footer class="footer"></footer>
    <!-- 登录模态框 -->
    <div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
      <div class="modal-dialog" role="document">
        <div class="modal-content">
          <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
            <h4 class="modal-title" id="myModalLabel">用户登录</h4>
          </div>
          <div class="modal-body">
            <form class="form-horizontal">
              <div class="form-group">
                <label for="inputEmail3" class="col-sm-2 control-label">Email</label>
                <div class="col-sm-10">
                  <input type="email" class="form-control" id="inputEmail3" placeholder="Email">
                </div>
              </div>
              <div class="form-group">
                <label for="inputPassword3" class="col-sm-2 control-label">Password</label>
                <div class="col-sm-10">
                  <input type="password" class="form-control" id="inputPassword3" placeholder="Password">
                </div>
              </div>
              <div class="form-group">
                <div class="col-sm-offset-2 col-sm-10">
                  <div class="checkbox">
                    <label>
                      <input type="checkbox"> Remember me
                    </label>
                  </div>
                </div>
              </div>
              <div class="form-group">
                <div class="col-sm-offset-2 col-sm-10">
                  <button type="submit" class="btn btn-default">Sign in</button>
                </div>
              </div>
            </form>           
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import bgImgOneBig from '../assets/slide_01_2000x410.jpg';
import bgImgTwoBig from '../assets/slide_02_2000x410.jpg';
import bgImgThreeBig from '../assets/slide_03_2000x410.jpg';

import bgImgOneTiny from '../assets/slide_01_640x340.jpg';
import bgImgTwoTiny from '../assets/slide_02_640x340.jpg';
import bgImgThreeTiny from '../assets/slide_03_640x340.jpg';

export default {
  data () {
    return {
     newsTitle:'全部新闻'
    }
  },
  methods:{
    init:function(){
      var startX;
      var endX;
      var offset = 50;
      var $carousels = $('.carousel');
      $carousels.on('touchstart',(e)=>{
        startX = e.originalEvent.touches[0].clientX;
      });
      $carousels.on('touchmove',(e)=>{
        endX = e.originalEvent.touches[0].clientX;
      });
      $carousels.on('touchend',(e)=>{
        var distance = Math.abs(startX - endX);
        if(distance > offset){
          $('.carousel').carousel(startX > endX ? 'next' : 'prev');
        }
      });
    },
    clickBtn:function(index){
      if(index == 0){
        this.newsTitle = '全部新闻';
      }else if(index == 1){
        this.newsTitle = '媒体新闻';
      }else if(index == 2){
        this.newsTitle = '行业资讯';
      }else{
        this.newsTitle = '金融时报';
      }
    },
    bgImgJudge:function(index){
      var screenWidth = document.body.clientWidth
      // 选项卡
      var ulContainer = $('.nav-tabs');
      var width = 30;
      ulContainer.children().each(function(index,el){
        width += el.clientWidth;
      })
      $('.nav-tabs').css('width',width);
      if(width > screenWidth){
        $('.ul-wapper').css('overflow-x','scroll');
      }else{
        $('.ul-wapper').css('overflow-x','hidden');
      }

      if(screenWidth > 768){
        if(index == '0'){
          return bgImgOneBig;
        }else if(index == '1'){
          return bgImgTwoBig;
        }else{
          return bgImgThreeBig;
        }
      }else{
        if(index == '0'){
          return bgImgOneTiny;
        }else if(index == '1'){
          return bgImgTwoTiny;
        }else{
          return bgImgThreeTiny;
        }
      }
    },
  },
  mounted(){
    this.init();
    $('[data-toggle="tooltip"]').tooltip();
    window.onresize = ()=>{
      console.log("调用了");
      this.bgImgJudge();
    }
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header{
  /* height: 200px; */
}
.header .topBar{
  height: 40px;
  border-bottom: 1px solid #c0c0c0;
}
.header .topBar .container .row div{
  height: 40px;
  line-height: 40px;
  font-size: 12px;
  color: #888;
}
.header .topBar .container .row a{
  color: #888;
}
.header .topBar .container .row a:hover{
  text-decoration:none;
}
.header .topBar .container .row a.btn-itcast{
  color: white;
}
.header .topBar .container .row div + div{
  border-left: 1px solid #c0c0c0;
}
.header .mobile-link img{
  display: none;
  position: absolute;
  top: 30px;
  left: 50%;
  margin-left: -60px;
  z-index: 10002;
}

/* 手机微金所二维码 */

.header .mobile-link:hover img{
  display: block;
  
}

/* 导航栏 */

.navbar-itcast {
  margin-bottom: 0px;
  top: 0px;
  width: 100%;
  background-color: #fff;
  border-color: #f5f5f5;
}

.navbar-itcast .navbar-brand {
  color: #777;
  height: 80px;
}

.navbar-itcast .navbar-brand:hover,
.navbar-itcast .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}

.navbar-itcast .navbar-text {
  color: #777;
}

.navbar-itcast .navbar-nav > li > a {
  color: #777;
  line-height: 72px;
  font-size: 14px;
}

.navbar-itcast .navbar-nav > li > a:hover,
.navbar-itcast .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
  border-bottom: 2px solid #e92322;
}

.navbar-itcast .navbar-nav > .active > a,
.navbar-itcast .navbar-nav > .active > a:hover,
.navbar-itcast .navbar-nav > .active > a:focus {
  color: #555;
  background-color: transparent;
  border-bottom: 2px solid #E92322;
}

.navbar-itcast .navbar-nav > .disabled > a,
.navbar-itcast .navbar-nav > .disabled > a:hover,
.navbar-itcast .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}

.navbar-itcast .navbar-toggle {
  border-color: #ddd;
  margin-top: 23px;
  margin-bottom: 23px;
}

.navbar-itcast .navbar-toggle:hover,
.navbar-itcast .navbar-toggle:focus {
  background-color: #ddd;
}

.navbar-itcast .navbar-toggle .icon-bar {
  background-color: #888;
}

.navbar-itcast .navbar-collapse,
.navbar-itcast .navbar-form {
  border-color: #e7e7e7;
}

.navbar-itcast .navbar-nav > .open > a,
.navbar-itcast .navbar-nav > .open > a:hover,
.navbar-itcast .navbar-nav > .open > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-itcast .navbar-brand {
  color: #777;
  height: 80px;  
}
.navbar-itcast .navbar-toggle{
  margin-top: 33px;
}
.header .icon-icon{
  font-size: 50px;
  color: red;
  line-height: 80px;
  vertical-align: middle;
}
.header .icon-logo{
  font-size: 30px;
  color: #000;
  line-height: 80px;
  vertical-align: middle;
}

/* 轮播图image */

.main_ad .carousel-inner .item img{
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}

/* 特色 */

.main_tese{
  border-bottom: 1px solid #c0c0c0;
}
.main_tese > .container > .row > div{
  margin: 45px 0px;
  height: 50px;
}
.main_tese > .container > .row > div i{
  font-size: 34px;
}
.icon-uniE907::before{
  content: "\e907";
}

/* 立即预约 */

.icon-uniE906::before{
  content: "\e906";
}
.icon-uniE905::before{
  content: "\e905";
}
.main_ljyy{
  padding: 20px 0px;
  border-bottom: 1px solid #c0c0c0;
}
.main_ljyy .container p{
  margin-bottom: 0px;
  font-size: 14px;
}
.main_ljyy .container p span,
.main_ljyy .container .pull-left a{
  color: #e92322;
}
.main_ljyy .container .pull-left a{
  border-bottom: 1px dashed #e92322;
}

/* 产品介绍 */

.main_prod{
  padding-bottom: 30px;
  background-color: #f0f0f0;
}
/* .main_prod .container .ul-wapper{
  overflow-x: scroll;
} */
.main_prod .container .nav-tabs{
  padding-top: 40px;
}
.main_prod .container .nav-tabs li{
}
.main_prod .container .nav-tabs li a{
  font-size: 16px;
  color: #333;
  background-color: transparent;
  border: 0px;
}
.main_prod .container .nav-tabs li a:hover{
  color: #000;
}
.main_prod .container .nav-tabs li.active{
  border-bottom: 4px solid #e92322;
} 
.main_prod .container .nav-tabs li.active a{
  color: #000;
}

/* .main_prod .container .tab-content .panel{
  border-radius: 0;
} */
.main_prod .panel-czbk{
  margin-top: 20px;
  border: 0;
  border-radius: 0;
  box-shadow: 1px 1px 5px #ccc;
}
.main_prod .panel-czbk.active::before{
  position: absolute;
  top: -11px;
  left: 0px;
  content: '\e915';
  font-family: itcast;
  font-size: 50px;
}
.main_prod .panel-czbk.active{
  position: relative;
  color: #fff;
  background-color: #E92322;
}
.main_prod .panel-czbk.disabled{
  background-color: #e0e0e0;
}
.main_prod .panel-czbk .panel-heading{
  position: relative;
  padding: 0px;
  padding-top: 50px;
  width: 120px;
  height: 150px;
  float: right;
  text-align: center;
  border-left: 1px dashed #c0c0c0;
}
.main_prod .panel-czbk .panel-heading .tooltips{
  position: absolute;
  width: 100%;
  top: 26px;
  text-align: center;
}
.main_prod .panel-czbk .panel-heading .tooltips .badge{
  margin: 3px;
  padding: 3px;
  display: inline-block;
  width: 20px;
  height: 20px;
  border-radius: 0px;
  border-width: 1px;
  border-style: solid;
  background-color: transparent;
}
.main_prod .panel-czbk .panel-heading .tooltips .badge .badge-one{
  color: #E92322;
  border-color: #E92322;
}
.main_prod .panel-czbk .panel-heading .tooltips .badge .badge-two{
  color: #337ab7;
  border-color: #337ab7;
}
.main_prod .panel-czbk .panel-heading p{
  margin-bottom: 0px;
}
.main_prod .panel-czbk .panel-heading p strong{
  font-size: 30px;
}
.main_prod .panel-czbk .panel-heading::before,
.main_prod .panel-czbk .panel-heading::after{
  position: absolute;
  content: ' ';
  width: 16px;
  height: 16px;
  border-radius: 10px;
  background-color: #f0f0f0;
}
.main_prod .panel-czbk .panel-heading::before{
  top: -8px;
  left: -8px;
}
.main_prod .panel-czbk .panel-heading::after{
  bottom: -8px;
  left: -8px;
  box-shadow: 0px 1px 1px #ccc inset;
}
.main_prod .panel-czbk .panel-body{
  /* padding: 0px;
  width: 120px;
  float: right; */
  height: 150px;
  margin-right: 120px;
}
.main_prod .panel-czbk .panel-body .row  p{
  margin-bottom: 0px;
}

/* 新闻列表 */
.main_news{
  padding: 50px 0px;
  border-bottom: 1px solid #c0c0c0;
}
.main_news .nav-pills li a{
  margin: 10px 0px;
  width: 60px;
  height: 60px;
  border-radius: 100%;
}
.main_news .nav-pills li.active a{
  background-color: #ec2130;
} 
.main_news .news-title{
  padding: 15px 0px;
  font-size: 18px;
  font-weight: 800;
  text-align: center;
  border-bottom: 1px dashed #c0c0c0;
}
.main_news .news-title::after{
  position: absolute;
  bottom: 0px;
  right: 0px;
  content: ' ';
  width: 10px;
  height: 10px;
  border-radius: 10px;
  border: 1px solid #c0c0c0;
}
/* 底部 */
.footer{
  height: 200px;
  background-color: yellow;
}

/* 合作伙伴 */

.main_hzhb{
  padding: 50px 0px;
}
.main_hzhb ul{
  position: relative;
  width: 910px;
  padding: 0px;
  list-style: none;
  overflow: hidden;
}
.main_hzhb ul li{
  float: left;
}
.main_hzhb ul li + li{
  border-left: 1px dashed #c0c0c0;
}
.main_hzhb ul li a{
  font-size: 50px;
  padding: 10px 25px;
  color: #888;
}
.main_hzhb ul li a:hover{
  text-decoration: none;
}
/* 图标样式 */

@font-face {
  font-family: 'itcast';
  src: url('../../static/font/MiFie-Web-Font.eot') format('embedded-opentype'), url('../../static/font/MiFie-Web-Font.svg') format('svg'), url('../../static/font/MiFie-Web-Font.ttf') format('truetype'), url('../../static/font/MiFie-Web-Font.woff') format('woff');
}

[class^="icon-"],
[class*=" icon-"] {
  font-family: itcast;
  font-style: normal;
}

.icon-mobilephone::before {
  content: "\e908";
  font-size: 13px;
}

.icon-telephone::before {
  content: "\e909";
  font-size: 15px;
}
.icon-logo::before {
  content: "\e93e";
}

.icon-icon::before {
  content: "\e920";
}
.icon-news01::before {
  content: "\e90f";
  font-size: 28px;
  color: #EAEAEA;
}

/* 合作伙伴 */
.icon-uniE930:hover {
  color: #df3232;
}

.icon-uniE930:before {
  content: "\e946";
}

.icon-uniE92F:hover {
  color: #e8380d;
}

.icon-uniE92F:before {
  content: "\e92f";
}

.icon-uniE92E:hover {
  color: #ed6f00;
}

.icon-uniE92E:before {
  content: "\e92e";
}

.icon-uniE92A:hover {
  color: #159f69;
}

.icon-uniE92A:before {
  content: "\e92a";
}

.icon-uniE929:hover {
  color: #07569e;
}

.icon-uniE929:before {
  content: "\e929";
}

.icon-uniE931:hover {
  color: #004098;
}

.icon-uniE931:before {
  content: "\e931";
}

.icon-uniE92C:hover {
  color: #d32019;
}

.icon-uniE92C:before {
  content: "\e92c";
}

.icon-uniE92B:hover {
  color: #3eac4a;
}

.icon-uniE92B:before {
  content: "\e92b";
}

.icon-uniE92D:hover {
  color: #2bb289;
}

.icon-uniE92D:before {
  content: "\e92d";
}
</style>
