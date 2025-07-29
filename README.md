# Myworld-app-import React from 'react';
import { View, Text, Button, StyleSheet, SafeAreaView, TouchableOpacity } from 'react-native';

export default function App() {
  return (
    <SafeAreaView style={styles.container}>
      <View style={styles.header}>
        <Text style={styles.title}>MyWorld</Text>
        <TouchableOpacity style={styles.messageButton}>
          <Text style={styles.messageText}>💬</Text>
        </TouchableOpacity>
      </View>
      
      <View style={styles.body}>
        <Text style={styles.text}>🔥 Добро пожаловать в MyWorld 🔥</Text>
        <Text style={styles.subtext}>Социальная сеть нового поколения</Text>
      </View>
      
      <View style={styles.footer}>
        <Button title="🏠 Домой" onPress={() => {}} />
        <Button title="🔍 Поиск" onPress={() => {}} />
        <Button title="👤 Профиль" onPress={() => {}} />
      </View>
    </SafeAreaView>
  );
}

const styles = StyleSheet.create({
  container: { flex: 1, backgroundColor: '#000', justifyContent: 'space-between' },
  header: { flexDirection: 'row', justifyContent: 'space-between', padding: 20, backgroundColor: '#111' },
  title: { fontSize: 24, color: '#f00' },
  messageButton: { backgroundColor: '#222', padding: 10, borderRadius: 10 },
  messageText: { fontSize: 20, color: '#0cf' },
  body: { alignItems: 'center', justifyContent: 'center', flex: 1 },
  text: { fontSize: 22, color: '#fff' },
  subtext: { fontSize: 16, color: '#888' },
  footer: { flexDirection: 'row', justifyContent: 'space-around', padding: 10, backgroundColor: '#111' }
});{
  "name": "myworld",
  "version": "1.0.0",
  "main": "App.js",
  "scripts": {
    "start": "expo start"
  },
  "dependencies": {
    "expo": "~50.0.0",
    "react": "18.2.0",
    "react-native": "0.73.0"
  }
}
