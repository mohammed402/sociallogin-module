# sociallogin-module
#Register socialloginmodule to the @NgModule import array
imports: [
  BrowserModule,
  SocialLoginModule
],
providers: [
  {
    provide: AuthServiceConfig,
    useFactory: provideConfig
  }
],
