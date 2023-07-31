# 1. Earthly Cloud Setup

Before we can get started, we have to setup a few things. This section is entirely optional if you already have installed the Earthly CLI and created and Earthly Cloud account. But it may make the workshop easier to follow along with if you read through it.

## 1. Sign in or Sign up for [Earthly Cloud](https://cloud.earthly.dev/login).

Once you have authenticated, you should see a screen that looks similar this:

![Earthly welcome screen](/assets/img/image.png)

## 2. Complete the "Install Earthly CLI" step

Click on the "Install Earthly CLI" button and follow the three steps to install the Earthly CLI, login to Earthly Cloud from your terminal, and confirm that you can run the "hello world" example.

## 3. Launch a Satellite

Click on the "Building in the Cloud" button at the top:

![Building in the cloud](/assets/img/c1-2.png)

These steps will walk you through creating your own [Earthly Satellite](https://earthly.dev/earthly-satellites)!

Make sure you write down the name of your satellite. We will need it later. But if you ever lose it you can find it again by running

```
earthly sat ls
```

This command will show any satellites you have in your account or organization.

In my case it prints:

```
 NAME       PLATFORM     SIZE   VERSION  STATE
   workshop1  linux/amd64  small  v0.7.13  operational
```

**Note**: If you are a member of multuple Earthly organizations you may have to pass the `--org` flag to satellite commands. For example: `earthly sat --org <your-org-name> ls`.

## 3. Complete the rest of the Getting Started tutorial

If you are a beginner to Earthly, we highly recommend that you complete the rest of the Getting Started tutorial. If will give you a solid foundation for the rest of the workshop.
