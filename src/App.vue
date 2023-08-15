<script setup>
import React from "react";
import "./nav.css";
import {Navlink} from "react-router-dom";

const Navbar = () => {
  return (
    <nav>
      <ul>
        <li>
          <NavLink to="/home">Home</NavLink>
          </li>
          <li>
            <NavLink to="/profile">Profile</NavLink>
            </li>
            <li>
              <NavLink to="/about">About</NavLink>
              </li>
              </ul>
              </nav>
  )
}

</script>

<template>

   
  
</template>

<style scoped>

</style>
