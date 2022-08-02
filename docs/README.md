# <a  href="https://projects.fuwa.sh/pint/"><img align="left" height="100" src="/docs/assets/pint-logo.png"/></a> **pint** (formerly gitccentify)

![rewrite-status](https://img.shields.io/badge/status-rewrite-orange)
![pint-status](https://img.shields.io/badge/pint-dev-red)
![gitccentify-status](https://img.shields.io/badge/gitccentify-released-green)
![chrome-web-store-version](https://img.shields.io/chrome-web-store/v/mjhmdkcefcklflcmmokoahfdodcpeobg)
![chrome-web-store-users](https://img.shields.io/chrome-web-store/users/mjhmdkcefcklflcmmokoahfdodcpeobg)

<hr>

> 💡 You are currently looking at the rebranded version of pint which is currently unreleased, the released one is located [here](https://github.com/fuwaa/pint/tree/v1)

[pint](https://projects.fuwa.sh/pint/) is a theming engine that allows you to rice your github experience.

![image](https://user-images.githubusercontent.com/53419401/180970561-02cc824d-f4e5-4935-97f0-560d3860b05a.png)
<br>
<br>

## installation

you can install this extension via the chrome web store (old version) or manually.

### chrome web store installation

> ⚠️ Please note that the version in the chrome web store is V1, which is very bad and outdated.

<a href="https://chrome.google.com/webstore/detail/gitccentify/mjhmdkcefcklflcmmokoahfdodcpeobg"><img src="https://storage.googleapis.com/web-dev-uploads/image/WlD8wC6g8khYWPJUsQceQkhXSlv1/UV4C4ybeBTsZt43U4xis.png" /></a>

### manual/source installation

1. clone this repository
2. run `yarn build` or `yabai`
3. open extension settings in chrome/brave/chromium
4. turn on developer mode
5. load unpacked extension
6. load the build folder

## roadmap

please check issue [#12](https://github.com/fuwaa/pint/issues/12) for more information :)

## limitations

> 💡 I am still looking for ways to better implement this! if you have any idea, please open an issue or create a pull request [here](https://github.com/fuwaa/pint/issues/new/choose)

The old implementation used a `setTimeout()` function, however the delay makes the project look like garbage as you can see the original colors before seeing your palette applied. The new implementation simply throws the entire css of github and unsets it while hiding the entire html making github look like an empty page until your palette gets loaded. Slight issue though, a flicker comes from time to time but it isn't noticable.

## documentation

Documentation is planned to debut on [fuwadocs](https://docs.fuwa.sh/pint/), however it is still in progress and is quite low on the priority queue.

## contributing

contributions are welcome ❤️. however, please do keep in mind that this is a very early project and things are bound to be messy. while code quality is my top priority, i'm currently implementing it ever so slowly.

## project structure

[![Structure](https://images.repography.com/27896465/fuwaa/pint/structure/a993ba4f490beac88c1084429e54e710_table.svg)](https://github.com/fuwaa/pint)

###### This extension is licensed under the GPLv3 License.

###### This project is not affiliated, associated, authorized, endorsed by, or in any way officially connected with GitHub, Inc. and Git, or any of its subsidiaries or its affiliates.
