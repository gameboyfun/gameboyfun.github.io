<template>
  <div>
    <NuxtIcon v-if="iconName === 'nuxt'" />
    <VueIcon v-if="iconName === 'vue'" />
    <ReactIcon v-if="iconName === 'react'" />
    <NextIcon v-if="iconName === 'next'" />
    <JavascriptIcon v-if="iconName === 'javascript'" />
    <TypescriptIcon v-if="iconName === 'typescript'" />
    <JestIcon v-if="iconName === 'jest'" />
    <PostmanIcon v-if="iconName === 'postman'" />
    <FlutterIcon v-if="iconName === 'flutter'" />
    <GitIcon v-if="iconName === 'git'" />
    <HtmlIcon v-if="iconName === 'html'" />
    <CssIcon v-if="iconName === 'css'" />
    <DartIcon v-if="iconName === 'dart'" />
    <Bootstrap4Icon v-if="iconName === 'bootstrap4'" />
    <TailwindIcon v-if="iconName === 'tailwind'" />
    <AngularIcon v-if="iconName === 'angular'" />
    <IonicIcon v-if="iconName === 'ionic'" />
    <JavaIcon v-if="iconName === 'java'" />
    <BitbucketIcon v-if="iconName === 'bitbucket'" />
    <AtlassianIcon v-if="iconName === 'atlassian'" />
    <JiraIcon v-if="iconName === 'jira'" />
    <ReduxIcon v-if="iconName === 'redux'" />
    <VscodeIcon v-if="iconName === 'vscode'" />
    <GithubIcon v-if="iconName === 'github'" />
    <GitlabIcon v-if="iconName === 'gitlab'" />
    <DockerIcon v-if="iconName === 'docker'" />
  </div>
</template>

<script>
import 'assets/css/glowing-icon.css'
import BitbucketIcon from './bitbucketIcon.vue'
import Bootstrap4Icon from './bootstrap4Icon.vue'
import CssIcon from './cssIcon.vue'
import DartIcon from './dartIcon.vue'
import FlutterIcon from './flutterIcon.vue'
import GitIcon from './gitIcon.vue'
import HtmlIcon from './htmlIcon.vue'
import IonicIcon from './ionicIcon.vue'
import JavaIcon from './javaIcon.vue'
import JavascriptIcon from './javascriptIcon.vue'
import JestIcon from './jestIcon.vue'
import NextIcon from './nextIcon.vue'
import NuxtIcon from './nuxtIcon.vue'
import PostmanIcon from './postmanIcon.vue'
import ReactIcon from './reactIcon.vue'
import TailwindIcon from './tailwindIcon.vue'
import TypescriptIcon from './typescriptIcon.vue'
import VueIcon from './vueIcon.vue'
import AngularIcon from './angularIcon.vue'
import AtlassianIcon from './atlassianIcon.vue'
import JiraIcon from './jiraIcon.vue'
import ReduxIcon from './reduxIcon.vue'
import VscodeIcon from './vscodeIcon.vue'
import GithubIcon from './githubIcon.vue'
import GitlabIcon from './gitlabIcon.vue'
import DockerIcon from './dockerIcon.vue'

export default {
  components: {
    NuxtIcon,
    VueIcon,
    ReactIcon,
    NextIcon,
    JavascriptIcon,
    JestIcon,
    TypescriptIcon,
    PostmanIcon,
    FlutterIcon,
    GitIcon,
    HtmlIcon,
    CssIcon,
    DartIcon,
    Bootstrap4Icon,
    TailwindIcon,
    AngularIcon,
    IonicIcon,
    JavaIcon,
    BitbucketIcon,
    AtlassianIcon,
    JiraIcon,
    ReduxIcon,
    VscodeIcon,
    GithubIcon,
    GitlabIcon,
    DockerIcon,
  },
  props: {
    iconName: {
      type: String,
      required: true,
    },
  },
}
</script>
