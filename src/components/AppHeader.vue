<template>
    <nav class="navbar navbar-expand navbar-dark bg-dark">
        <a class="navbar-brand">Ứng dụng quản lý truyện tranh</a>
        <div class="mr-auto navbar-nav">
            <li class="nav-item">
                <router-link :to="{ name: 'contactbook' }" class="nav-link">
                    Truyện
                   
                </router-link>
            </li>
            
            <li class="nav-item">
                <router-link :to="{ name: 'authorbook' }" class="nav-link">
                    Tác giả
                </router-link>
            </li>
        </div>
    </nav>
</template>