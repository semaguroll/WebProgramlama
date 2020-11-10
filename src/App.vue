<template>
  <v-app>
    
    
   <v-main>
     
      <HelloWorld/>
      <Menu/>
      <Size/>     
      <Detail/>
      <ShoppingCart/> 
      <Eposta/>     
      <Login/>
      <NewUser/>
      <UserInfo/>
       <Products/>
      
      
   
   </v-main>
      
    
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Menu from './components/Menu';
import Size from './components/Size';
import Products from './components/Products';
import Detail from './components/Detail';
import ShoppingCart from './components/ShoppingCart';
import Eposta from './components/Eposta';
import Login from './components/Login';
import NewUser from './components/NewUser';
import UserInfo from './components/UserInfo';

export default {
  name: 'App',

  components: {
    HelloWorld,
    Menu,
    Size ,
    Products,
    Detail,
    ShoppingCart,
    Eposta,
    Login,
    NewUser,
    UserInfo
  },

  data: () => ({
    //
  }),
};
</script>
