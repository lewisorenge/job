<template>
    <div class="sidebar" style=" padding-top:5.2%;" data-color="purple" data-image="img/sidebar-1.jpg">
        <!--USER-->
        <div class="dropdown show" style="z-index:6; position:absolute; top:-5px; right:-5px;">
            <a class="btn btn-default dropdown-toggle" href="#" role="button" id="dropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><i class="fa fa-user-circle"></i> <span
                style="text-transform: capitalize;" class="user-profile-text">Rohan Sulaiman ... <i
                class="fa fa-angle-down"></i></span></a>
            <div style="z-index:5;" class="dropdown-menu" aria-labelledby="dropdownMenuLink">
                <div style="padding:8px" class="btn-group btn-group-justified btn-group-sm" data-ng-click="$event.stopPropagation()" data-eo-halt="check($event)">
                    <label id="online" class="btn btn-default ng-untouched ng-valid ng-not-empty ng-dirty ng-valid-parse active" data-ng-model="dash.visibility" data-ng-click="setVisibility('VISIBLE')" data-eo-btn-radio="'VISIBLE'">Online</label>
                    <label id="invisible" class="btn btn-light ng-untouched ng-valid ng-not-empty ng-dirty label-bg-2" data-ng-model="dash.visibility" data-ng-click="setVisibility('INVISIBLE')" data-eo-btn-radio="'INVISIBLE'" title="Appear offline to other users">Invisible</label>
                </div>
                <li><a class="dropdown-item" href="#"><i class="fa fa-user-circle"></i><span> Rohan Sulaiman</span></a>
                </li>
                <li><a class="dropdown-item" href="settings.html"><i
                    class="fa fa-cog"></i> Setting</a></li>
                <li><a class="dropdown-item" href="login.html"><i
                    class="fa fa-sign-out"></i> Logout</a></li>
            </div>
        </div>
        <!-- START SIDE WRAPPER -->
        <div class="sidebar-wrapper" style="z-index:4; height:100%;">
            <ul class="nav">
                <router-link tag="li" to="/" exact>
                    <a href="/">
                        <span class="icon-btn">
                            <i class="fa fa-home"></i>
                        </span>
                        <p>Home</p>
                    </a>
                </router-link>
                <router-link tag="li" to="/joboffers">
                    <a href="/joboffers">
                        <span class="icon-btn">
                            <i class="fa fa-bullhorn"></i>
                        </span>
                        <p>Job Offers</p>
                    </a>
                </router-link>
                <router-link tag="li" to="/jobactivity">
                    <a href="/jobactivity">
                        <span class="icon-btn">
                            <i class="fa fa-check-square-o"></i>
                        </span>
                        <p>Job Activity</p>
                    </a>
                </router-link>
                <router-link tag="li" to="/jobcontracts">
                    <a href="/jobcontracts">
                        <span class="icon-btn">
                            <i class="fa fa-check-square-o"></i>
                        </span>
                        <p>Job Contracts</p>
                    </a>
                </router-link>

                <router-link tag="li" to="/saleservices">
                    <a href="/saleservices">
                        <span class="icon-btn">
                            <i class="fa fa-cart-plus" aria-hidden="true"></i>
                        </span>
                    <p>Sale Services</p>
                </a>
                </router-link>
                <router-link tag="li" to="/mypayments">
                    <a href="/mypayments">
                        <span class="icon-btn">
                            <i class="fa fa-money"></i>
                        </span>
                    <p>My Payments</p>
                </a>
                </router-link>
                <router-link tag="li" to="/mycoins">
                    <a href="/mycoins">
                        <span class="icon-btn">
                            <i class="fa fa-btc"></i>
                        </span>
                    <p>My Coins</p>
                </a>
                </router-link>
                <router-link tag="li" to="/myappointments">
                    <a href="/myappointments">
                        <span class="icon-btn">
                            <i class="fa fa-calendar-check-o"></i>
                        </span>
                    <p>My Appointments</p>
                </a>
                </router-link>
                <router-link tag="li" to="/purchasehistory">
                    <a href="/purchasehistory">
                        <span class="icon-btn">
                            <i class="fa fa-line-chart"></i>
                        </span>
                    <p>Purchase History</p>
                </a>
                </router-link>
                <router-link tag="li" to="/searchemployer">
                    <a href="searchemployer.html">
                        <span class="icon-btn">
                            <i class="fa fa-briefcase"></i>
                        </span>
                    <p>Search Employer</p>
                </a>
                </router-link>
                <router-link tag="li" to="/myreviews">
                    <a href="/myreviews">
                        <span class="icon-btn">
                            <i class="fa fa-comments-o"></i>
                        </span>
                    <p>My Reviews</p>
                </a>
                </router-link>
                <router-link tag="li" to="/mywarranty">
                    <a href="/mywarranty">
                        <span class="icon-btn">
                            <i class="fa fa-cogs"></i>
                        </span>
                    <p>My Warranty</p>
                </a>
                </router-link>
                <router-link tag="li"  to="/myteam">
                    <a href="/myteam">
                        <span class="icon-btn">
                            <i class="fa fa-users"></i>
                        </span>
                    <p>Tasks &amp; Employee</p>
                </a>
                </router-link>
                <router-link tag="li" to="/myclients">
                    <a href="/myclients">
                        <span class="icon-btn">
                            <i class="fa fa-user-circle"></i>
                        </span>
                    <p>My Clients</p>
                </a>
                </router-link>
                <router-link tag="li" to="/myincome">
                    <a href="/myincome">
                        <span class="icon-btn">
                            <i class="fa fa-pie-chart"></i>
                        </span>
                    <p>My Income</p>
                </a>
                </router-link>
            </ul>
        </div>
    </div>
</template>