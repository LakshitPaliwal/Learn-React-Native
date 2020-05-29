```reactjs
import React from 'react';

import { Appbar,Text } from 'react-native-paper';
import { StyleSheet, View, SafeAreaView,Image } from 'react-native';
export default function App() {
const handlePress=()=>alert("text presssed")
  
  return (

  <View>
        <Appbar.Header>
              <Appbar.Content
                title="First React App"
                alignItems="center"
              />
        </Appbar.Header>
     <Text onPress={(handlePress)}>lakshit paliwal Open up App.js to start working on your app!</Text>
      <Image source={{
        width:200,
        height:300,
        uri:"https://source.unsplash.com/random",
      }} />
       
</View>
    
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: "dodgerblue",
    alignItems: 'center',
    justifyContent: 'center',
  },
});

```
