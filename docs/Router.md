---
id: Router
title: Router
---

By using router you can easily achieve routing from one page to another page.

## Accessing Routes
Open the Router folder present in the root directory to access the router file.

```
cd router
touch intex.tsx
```

```
<ConfigContext.Provider value={configReducer}>
    <ThemedView style={style.container}>
        <NativeRouter>
            <BackHandlerHOC>
                <Switch>
                    <Route exact path="/" component={BaseHome} />
                    <Route exact path="/login/" component={Login} />
                    <Route exact path="/signup/" component={Signup} />
                    <Route exact path="/forget/" component={ForgetPassword} />
                    <Route exact path="/gender/" component={Gender} />
                    <Route exact path="/matching/" component={Matching} />
                    <Route exact path="/matched/" component={Matched} />
                    <Route exact path="/searching/" component={Searching} />
                    <Route exact path="/nearby/" component={Nearby} />
                    <Route exact path="/profile/" component={Profile} />
                    <Route exact path="/edit/" component={EditProfile} />
                    <Route exact path="/calling/" component={Calling} />
                    <Route exact path="/video/" component={VideoCall} />
                    <Route exact path="/premium/" component={Premium} />
                    <Route exact path="/message/" component={Message} />
                    <Route exact path="/process/" component={PaymentProcess} />
                    <Route exact path="/card/" component={NewCard} />
                    <Route exact path="/payment/" component={Payment} />
                </Switch>
            </BackHandlerHOC>
        </NativeRouter>
    </ThemedView>
</ConfigContext.Provider>
```

As you can see there are various route defined in the above mentioned file. You can add more route to use in the chat app.