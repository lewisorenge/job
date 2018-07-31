<template>
    <header>
        <div class="w-100">
            <!--first-menu-->

            <div class="topnav" id="myTopnav">
                <div v-if="$route.path==='/'">
                    <a class="responsive-logo">
                        <img src="img/logo.png">
                    </a>
                </div>

                <div v-else>
                    <a class="responsive-logo">
                        <img src="img/header/logo.jpeg">
                    </a>
                </div>
                <div class="appointmentt">
                    <a class="dropdown-toggle" id="apointments" href="#" role="button" data-toggle="dropdown">
                    <i aria-hidden="true" id="shape" class="fa fa-calendar-times-o"></i>
                    <span class="noty-bubble" id="bubble">
                            2
                        </span>
                </a>
                    <!-- Dropdown Apointment-->
                    <div class="dropdown-menu">
                        <div class="notification-container">
                            <h3>Notifications
                            <i class="material-icons dp48 right">settings</i>
                        </h3>
                            <input class="checkbox" type="checkbox" id="size_1" value="small" checked/>
                            <label class="notification new" for="size_1"><em>1</em> new <a href="">guest
                            account(s)</a> have been created.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_2" value="small" checked/>
                            <label class="notification new" for="size_2"><em>3</em> new <a href="">lead(s)</a> are available in the system.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_3" value="small" checked/>
                            <label class="notification" for="size_3"><em>5</em> new <a href="">task(s)</a>.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_4" value="small" checked/>
                            <label class="notification" for="size_4"><em>9</em> new <a href=""> event(s)</a> are scheduled for today.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_5" value="small" checked/>
                            <label class="notification" for="size_5"><em>1</em> blog post <a href="">comment(s)</a> need approval.<i class="material-icons dp48 right">clear</i></label>
                        </div>
                    </div>
                </div>
                <!-- End of dropdown-->
                <a id="chat" href="chat.html">
                <i aria-hidden="true" id="shape" class="fa fa-envelope-open-o">
                </i>
                <span class="noty-bubble bubble-green" id="bubble">
                        15
                    </span>
            </a>
                <!--Job Offers section-->
                <div class="job-offers">
                    <a class="dropdown-toggle" role="button" data-toggle="dropdown" id="joboffers" href="#">
                    <i aria-hidden="true" id="shape" class="fa fa-bullhorn">
                    </i>
                    <span class="noty-bubble bubble-blue" id="bubble">
                            2
                        </span>
                </a>
                    <!-- Dropdown  Joboffers -->
                    <div class="dropdown-menu" aria-labelledby="joboffers">
                        <div class="notification-container">
                            <h3>Notifications
                            <i class="material-icons dp48 right">settings</i>
                        </h3>
                            <input class="checkbox" type="checkbox" id="size_1" value="small" checked/>
                            <label class="notification new" for="size_1"><em>1</em> new <a href="">guest
                            account(s)</a> have been created.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_2" value="small" checked/>
                            <label class="notification new" for="size_2"><em>3</em> new <a href="">lead(s)</a> are available in the system.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_3" value="small" checked/>
                            <label class="notification" for="size_3"><em>5</em> new <a href="">task(s)</a>.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_4" value="small" checked/>
                            <label class="notification" for="size_4"><em>9</em> new <a href=""> event(s)</a> are scheduled for today.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_5" value="small" checked/>
                            <label class="notification" for="size_5"><em>1</em> blog post <a href="">comment(s)</a> need approval.<i class="material-icons dp48 right">clear</i></label>
                        </div>
                    </div>
                </div>
                <!-- End of dropdown-->
                <!-- Info sections -->
                <div class="infoo">
                    <a class="dropdown-toggle" role="button" data-toggle="dropdown" id="info" href="#Info">
                    <i aria-hidden="true" id="shape" class="fa fa-info-circle">
                    </i>
                    <span class="noty-bubble bubble-purple" id="bubble">
                            2
                        </span>
                </a>
                    <!-- Dropdown   Info-->
                    <div class="dropdown-menu">
                        <div class="notification-container">
                            <h3>Notifications
                            <i class="material-icons dp48 right">settings</i>
                        </h3>
                            <input class="checkbox" type="checkbox" id="size_1" value="small" checked/>
                            <label class="notification new" for="size_1"><em>1</em> new <a href="">guest
                            account(s)</a> have been created.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_2" value="small" checked/>
                            <label class="notification new" for="size_2"><em>3</em> new <a href="">lead(s)</a> are available in the system.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_3" value="small" checked/>
                            <label class="notification" for="size_3"><em>5</em> new <a href="">task(s)</a>.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_4" value="small" checked/>
                            <label class="notification" for="size_4"><em>9</em> new <a href=""> event(s)</a> are scheduled for today.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_5" value="small" checked/>
                            <label class="notification" for="size_5"><em>1</em> blog post <a href="">comment(s)</a> need approval.<i class="material-icons dp48 right">clear</i></label>
                        </div>
                    </div>
                </div>
                <!-- End of dropdown-->
                <div class="creditss">
                    <a class="dropdown-toggle" role="button" data-toggle="dropdown" id="credit" href="#Credit">
                    <i aria-hidden="true" id="shape" class="fa fa-life-ring">
                    </i>
                    <span class="noty-bubble bubble-red" id="bubble">
                            2
                        </span>
                </a>
                    <!-- Dropdown  Credit-->
                    <div class="dropdown-menu">
                        <div class="notification-container">
                            <h3>Notifications
                            <i class="material-icons dp48 right">settings</i>
                        </h3>
                            <input class="checkbox" type="checkbox" id="size_1" value="small" checked/>
                            <label class="notification new" for="size_1"><em>1</em> new <a href="">guest
                            account(s)</a> have been created.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_2" value="small" checked/>
                            <label class="notification new" for="size_2"><em>3</em> new <a href="">lead(s)</a> are available in the system.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_3" value="small" checked/>
                            <label class="notification" for="size_3"><em>5</em> new <a href="">task(s)</a>.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_4" value="small" checked/>
                            <label class="notification" for="size_4"><em>9</em> new <a href=""> event(s)</a> are scheduled for today.<i class="material-icons dp48 right">clear</i></label>
                            <input class="checkbox" type="checkbox" id="size_5" value="small" checked/>
                            <label class="notification" for="size_5"><em>1</em> blog post <a href="">comment(s)</a> need approval.<i class="material-icons dp48 right">clear</i></label>
                        </div>
                    </div>
                </div>
                <!-- End of dropdown-->
                <!-- <a id="set-ng" class="menu-settings" href="settings.html">
                <i aria-hidden="true" id="shape" class="fa fa-cogs"></i>
            </a>  -->
                <a href="javascript:void(0);" style="font-size:-webkit-xxx-large;" class="icon" onclick="responsive_header()">&#9776;</a>
            </div>
            <!--fm-end-->
        </div>

        <!-- For specific routes -->
        <div v-if="$route.path==='/joboffers'" class="searchbar">
        
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="offers tab">
            </div>
            <div class="sortbox" style="width:50%">
                <span class="custom-dropdown">
                    <select>
                        <option>Sort By Budget</option>
                        <option>Option 1</option>
                        <option>Option 2</option>
                    </select>
                </span>
                <span class="custom-dropdown">
                    <select>
                        <option>Sort By Category</option>
                        <option>Option 1</option>
                        <option>Option 2</option>
                    </select>
                </span>
            </div>
            <div class="search-container">
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- Job Activity -->
        <div v-else-if="$route.path==='/jobactivity'" class="searchbar search-bar-b" style="position: absolute; z-index:-3; top:70px;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li role="presentation" class="active"><a href="#bids" aria-controls="bids" role="tab" data-toggle="tab"><i class="fa fa-bullhorn" style="width:auto" aria-hidden="true"></i> Bids </a></li>
                    <li role="presentation"><a href="#denied" aria-controls="denied" role="tab" data-toggle="tab"><i class="fa fa-hand-paper-o" style="width:auto" aria-hidden="true"></i> Denied </a></li>
                    <li role="presentation"><a href="#reported" aria-controls="reported" role="tab" data-toggle="tab"><i class="fa fa-exclamation-triangle" aria-hidden="true" style="width:auto"></i> Reported </a></li>
                    <li role="presentation"><a href="#bookmark" aria-controls="bookmark" role="tab" data-toggle="tab"><i class="fa fa-bookmark" style="width: 27px;" aria-hidden="true"></i> Remember </a></li>
                </ul>
            </div>
            <div class="search-container">
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- Job Contracts -->
        <div v-else-if="$route.path==='/jobcontracts'" class="searchbar" style="z-index:2;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li style="z-index: 1;" role="presentation" class="active"><a href="#ContractCanceled_accept" aria-controls="ContractCanceled_accept" role="tab" data-toggle="tab"><i class="fa fa-bullhorn" aria-hidden="true" style="width:auto"></i> Accepted Offers </a></li>
                    <li style="z-index: 1;" role="presentation"><a href="#ContractStarted" aria-controls="ContractStarted" role="tab" data-toggle="tab"><i class="fa fa-play" aria-hidden="true" style="width:27px;"></i> Started </a></li>
                    <li style="z-index: 1;" role="presentation"><a href="#ContractDone" aria-controls="ContractDone" role="tab" data-toggle="tab"><i class="fa fa-check-square-o" aria-hidden="true" style="width:auto"></i> Done </a></a>
                    </li>
                    <li style="z-index: 1;" role="presentation"><a href="#ContractDeliverd" aria-controls="ContractDeliverd" role="tab" data-toggle="tab"><i class="fa fa-thumbs-o-up" aria-hidden="true" style="width:auto"></i> Deliverd </a></li>
                    <li style="z-index: 1;" role="presentation"><a href="#ContractDisputs" aria-controls="ContractDisputs" role="tab" data-toggle="tab"><i class="fa fa-exclamation-triangle" aria-hidden="true" style="width:auto"></i>  Disputs </a></li>
                    <li style="z-index: 1;" role="presentation"><a href="#ContractCanceled" aria-controls="ContractCanceled" role="tab" data-toggle="tab"><i class="fa fa-ban" aria-hidden="true" style="width:auto"></i> Canceled </a></li>
                </ul>
            </div>
            <div class="search-container">
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- Sale Services -->
        <div v-else-if="$route.path==='/saleservices'" class="searchbar sales search-bar-b col-md-12 search-custom" style="z-index:-3;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="col-md-9 tab search-custom" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li role="presentation" class="active"><a href="#BestSeller" aria-controls="BestSeller" role="tab" data-toggle="tab"><i
                        class="fa  fa-thumbs-o-up" aria-hidden="true" style="width:auto"></i> Best Seller </a>
                    </li>
                    <li role="presentation"><a href="#ManageServices" aria-controls="ManageServices" role="tab" data-toggle="tab"><i class="fa fa-cog" aria-hidden="true"
                                                                style="width:auto"></i> Manage Services </a>
                    </li>
                    <li role="presentation"><a href="#ManageItems" aria-controls="ManageItems" role="tab" data-toggle="tab"><i class="fa fa-wrench" aria-hidden="true"
                                                                style="width:auto"></i> Manage Items </a></li>
                    <li role="presentation"><a href="#SaleHistory" aria-controls="SaleHistory" role="tab" data-toggle="tab"><i class="fa fa-history" aria-hidden="true"
                                                                style="width:auto"></i> Sale History </a></li>
                </ul>
            </div>
            <div class="col-md-3 search-container search custom-search search-custom">
                <button type="button" data-toggle="modal" data-target="#bestselleraddnewservice" class="btn btn-block btn-grey btn-xs aligncenter addService">+ | Add Service
                </button>
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- My payments -->
        <div v-else-if="$route.path==='/mypayments'" class="searchbar" style="z-index: 2;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab container search-mypayments" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li style="z-index: 1;" role="presentation" class="active  search-mypayments"><a href="#OnMilestone" aria-controls="OnMilestone" role="tab" data-toggle="tab" aria-expanded="true"> <i class="fa fa-university" aria-hidden="true" style="width:auto"></i> On Milestone </a></li>
                    <li style="z-index: 1;" role="presentation" class=" search-mypayments"><a href="#ApproveRequest" aria-controls="ApproveRequest" role="tab" data-toggle="tab" aria-expanded="false"> <i class="fa fa-exchange" aria-hidden="true" style="width:auto"></i> Approve Request </a></li>
                    <li style="z-index: 1;" role="presentation" class=" search-mypayments"><a href="#Refundrequest" aria-controls="Refundrequest" role="tab" data-toggle="tab" aria-expanded="false"> <i class="fa fa-undo " aria-hidden="true" style="width:auto"></i> Refund request </a></li>
                    <li style="z-index: 1;" role="presentation" class=""><a href="#Payouts" aria-controls="Payouts" role="tab" data-toggle="tab" aria-expanded="false"> <i class="fa fa-eur " aria-hidden="true" style="width:auto; padding: 5px 8px;"></i> Payouts </a></li>
                    <li style="z-index: 1; margin-top: 4px" role="presentation" class=""><a href="#Invoice" aria-controls="Invoice" role="tab" data-toggle="tab" aria-expanded="false"> <i class="fa fa-file-text-o" aria-hidden="true" style="width:auto"></i> Invoice </a></li>
                </ul>
            </div>
            <div class="search-container">
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- My coins -->
        <div v-else-if="$route.path==='/mycoins'" class="searchbar sales" style="z-index:2;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li style="z-index: 1;" role="presentation" class="active"><a href="#purchase" aria-controls="purchase" role="tab" data-toggle="tab"><i class="fa fa-cart-plus" aria-hidden="true" style="width:auto"></i> Purchase </a></li>
                    <li style="z-index: 1;" role="presentation"><a href="#used" aria-controls="used" role="tab" data-toggle="tab"><i class="fa fa-cart-plus" aria-hidden="true" style="width:auto"></i> Used </a></li>
                </ul>
            </div>
            <div class="search-container search custom-search">
                <button type="button" data-toggle="modal" data-target="#MatchedEmployeerCoins" class="btn btn-block btn-grey btn-xs aligncenter addService">+ | Add Coins</button>
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- My Appointments -->
        <div v-else-if="$route.path==='/myappointments'" class="searchbar" style="z-index:2;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li style="z-index:1;" role="presentation" class="active"><a href="#NewAppointments" aria-controls="NewAppointments" role="tab" data-toggle="tab"><i
                        class="fa fa-calendar-plus-o" aria-hidden="true" style="width:auto"></i> New
                    Appointments </a></li>
                    <li style="z-index:1;" role="presentation"><a href="#AcceptedAppointments" aria-controls="AcceptedAppointments" role="tab" data-toggle="tab"><i
                        class="fa fa-calendar-check-o " aria-hidden="true" style="width:auto"></i> Accepted
                    Appointments </a></li>
                    <li style="z-index:1;" role="presentation"><a href="#DeniedAppointments" aria-controls="DeniedAppointments" role="tab" data-toggle="tab"><i
                        class="fa fa-calendar-times-o" aria-hidden="true" style="width:auto"></i> Denied
                    Appointments </a></li>
                    <li style="z-index:1;" role="presentation"><a href="#Interviews" aria-controls="Interviews" role="tab" data-toggle="tab"><i
                        class="fa fa-history" aria-hidden="true" style="width:auto"></i> Interviews </a></li>
                </ul>
            </div>
            <div class="search-container">
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- Purchase History -->
        <div v-else-if="$route.path==='/purchasehistory'" class="searchbar" style="z-index:2;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li style="z-index: 1;" role="presentation" class="active"><a href="#ServicePurchase" aria-controls="ServicePurchase" role="tab" data-toggle="tab"><i
                        class="fa fa-shopping-basket" style="width:auto" aria-hidden="true"></i> Service Sale
                </a></li>
                    <li style="z-index: 1;" role="presentation"><a href="#ItemPurchase" aria-controls="ItemPurchase" role="tab" data-toggle="tab"><i
                        class="fa fa-shopping-cart" style="width:auto" aria-hidden="true"></i> Item Sale </a>
                    </li>
                </ul>
            </div>
            <div class="search-container">
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- Search employer -->
        <div v-else-if="$route.path==='/searchemployer'" class="searchbar sales" style="z-index: 2;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li style="z-index: 1;" role="presentation" class="active"><a href="#MatchedEmployeer"
                                                                                    aria-controls="MatchedEmployeer"
                                                                                    role="tab" data-toggle="tab"><i
                            class="fa fa-graduation-cap " aria-hidden="true" style="width:auto"></i> Matched
                        Employeer </a></li>
                    <li style="z-index: 1;" role="presentation"><a href="#MyJobOffers" aria-controls="MyJobOffers"
                                                                    role="tab" data-toggle="tab"><i
                            class="fa fa-briefcase " aria-hidden="true" style="width:auto"></i> My Job Offers </a>
                    </li>
                    <li style="z-index: 1;" role="presentation"><a href="#WorkRequest" aria-controls="WorkRequest"
                                                                    role="tab" data-toggle="tab"><i
                            class="fa fa-hand-paper-o" aria-hidden="true" style="width:auto"></i> Work Request </a>
                    </li>
                    <li style="z-index:1;" role="presentation"><a href="#Interviews" aria-controls="Interviews"
                                                                    role="tab" data-toggle="tab"><i
                            class="fa fa-history" aria-hidden="true" style="width:auto"></i> Interviews </a>
                    </li>
                </ul>
            </div>
            <div class="search-container">
                <button type="button" data-toggle="modal" data-target="#AddsearchMatchedEmployeer"
                        class="btn btn-block btn-grey btn-xs aligncenter addService">+ | Add Employee
                    <div class="ripple-container"></div>
                </button>
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- My reviews -->
        <div v-else-if="$route.path==='/myreviews'" class="searchbar sales" style="z-index:2;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li style="z-index:1;" role="presentation" class="active"><a href="#Unseenreview" aria-controls="Unseenreview" role="tab" data-toggle="tab"><i
                        class="fa fa-eye-slash " aria-hidden="true" style="width:auto"></i> Unseen Reviews </a>
                    </li>
                    <li style="z-index:1;" role="presentation"><a href="#AllReviews" aria-controls="AllReviews" role="tab" data-toggle="tab"><i
                        class="fa fa-comments-o " aria-hidden="true" style="width:auto"></i> All Reviews </a>
                    </li>
                </ul>
            </div>
            <div class="search-container search custom-search">
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- My warranty -->
        <div v-else-if="$route.path==='/mywarranty'" class="searchbar" style="z-index:2;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li style="z-index:1;" role="presentation" class="active"><a href="#CurrentWarranty" aria-controls="CurrentWarranty" role="tab" data-toggle="tab"><i class="fa fa-percent " style="width:auto" aria-hidden="true"></i> Service Warranty </a></li>
                    <li style="z-index:1;" role="presentation"><a href="#WarrantyExpired" aria-controls="WarrantyExpired" role="tab" data-toggle="tab"><i class="fa fa-shopping-cart" style="width:auto" aria-hidden="true"></i> My Purchase Warranty </a></li>
                </ul>
            </div>
            <div class="search-container">
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- Tasks and Employee -->
        <div v-else-if="$route.path==='/myteam'" class="searchbar sales" style="z-index: 2;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li style="z-index: 1;" role="presentation" class="active"><a href="#MyTeam235" aria-controls="MyTeam235" role="tab" data-toggle="tab"><i
                        class="fa fa-users " style="width:auto" aria-hidden="true"></i> My Team </a></li>
                    <li style="z-index: 1;" role="presentation"><a href="#OurTasks5154" aria-controls="OurTasks5154" role="tab" data-toggle="tab"><i
                        class="fa fa-tasks" style="width:auto" aria-hidden="true"></i> Our Tasks </a></li>
                </ul>
            </div>
            <div class="search-container search custom-search">
                <button type="button" data-toggle="modal" data-target="#addnewteam" class="btn btn-block btn-grey btn-xs aligncenter addService">+ | Add Employee
                </button>
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>

        <!-- My Clients -->
        <div v-else-if="$route.path==='/myclients'" class="searchbar" style="z-index:-3;">
            <a id="nav2button" href="javascript:void(0);" class="icon" onclick="responsive_header2()">&#9196;</a>
            <div class="tab" role="tabpanel">
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li role="presentation" class="active"><a href="#CompanyClients" aria-controls="CompanyClients" role="tab" data-toggle="tab"><i class="fa fa-industry" style="width:auto" aria-hidden="true"></i> Company Clients </a></li>
                    <li role="presentation"><a href="#UserClients" aria-controls="UserClients" role="tab" data-toggle="tab"><i class="fa fa-user-circle-o" style="width:auto" aria-hidden="true"></i> User Clients </a></li>
                </ul>
            </div>
            <div class="search-container">
                <form action="">
                    <input type="text" placeholder="Search.." name="search">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
            </div>
        </div>
    </header>
</template>