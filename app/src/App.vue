<template>
  <div class="bg-cyan-400 w-screen h-screen overflow-hidden">
    <div
      class="container grid grid-cols-2 justify-center align-center bg-white w-9/12 h-4/5 mx-auto my-16 rounded-lg overflow-hidden"
    >
      <img
        class="w-full h-full bg-cyan-200 rounded-lg"
        src="./assets/Ikbal 4.png"
        alt=""
      />
      <div>
        <h1 class="text-center text-cyan-400 font-bold text-3xl my-6">
          Sign In
        </h1>
        <div
          class="inline-grid grid-cols-3 place-content-center w-full justify-center mx-2"
        >
          <span class="justify-self-end"
            ><img src="./assets/Github.png" alt=""
          /></span>
          <span class="justify-self-center"
            ><img src="./assets/Twitter.png" alt=""
          /></span>
          <span class="justify-self-start"
            ><img src="./assets/Facebook.png" alt=""
          /></span>
        </div>
        <p class="text-center text-sm font-light">Or sign in with your email</p>
        <form action="#">
          <div class="form-control my-4">
            <label for="email" class="w-full mx-16 font-bold">Email</label
            ><br />
            <input
              type="email"
              placeholder="Please enter your mail"
              class="w-9/12 h-9 border-2 border-x-0 border-t-0 mx-16 px-2 rounded hover:border-t-2 hover:border-x-2"
            />
          </div>
          <div class="form-control my-4">
            <label for="password" class="w-full mx-16 font-bold"
              >Password</label
            >
            <br />
            <input
              type="password"
              placeholder="Please enter your password"
              class="w-9/12 h-9 border-2 border-x-0 border-t-0 mx-16 px-2 rounded hover:border-t-2 hover:border-x-2"
            />
          </div>
          <div class="form-control my-4 mx-16">
            <input type="checkbox" name="checkbox" id="" />
            <span class="font-light text-sm">Keep me signed in</span>
          </div>
          <div class="form-control my-4 mx-16">
            <button
              type="submit"
              class="w-full h-9 rounded-md font-bold bg-cyan-400"
            >
              Submit
            </button>
          </div>
          <div class="form-control my-2 mx-16">
            <a href="#" class="no-underline font-bold text-sm text-rose-400"
              >Forgot password</a
            >
          </div>
          <div class="form-control my-0 mx-16">
            <a href="#" class="text-sm font-bold text-cyan-400 no-underline">
              Sign up
            </a>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>
