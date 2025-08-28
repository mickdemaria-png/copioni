import 'package:flutter/material.dart';

void main() {
  runApp(const ScriptLearnerApp());
}

class ScriptLearnerApp extends StatelessWidget {
  const ScriptLearnerApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Script Learner',
      theme: ThemeData(primarySwatch: Colors.blue),
      home: const HomePage(),
    );
  }
}

class HomePage extends StatelessWidget {
  const HomePage({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: const Text("Script Learner")),
      body: const Center(
        child: Text(
          "Benvenuto!\nCarica un copione per iniziare.",
          textAlign: TextAlign.center,
        ),
      ),
    );
  }
}

