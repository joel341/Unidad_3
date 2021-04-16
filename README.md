# Unidad_3
compilacion_y_depuracion_de_codigo


#arduino_voice _master

![image](https://user-images.githubusercontent.com/79875834/115074877-e6059600-9ebf-11eb-913e-b4c346beb5d6.png)

//importamos libreias como bluetooth serial el cual tendremos una comunicasion serial con equipos ya que despues llamamos de las librerias.
![image](https://user-images.githubusercontent.com/79875834/115074903-f158c180-9ebf-11eb-9300-074587c7c8d9.png)

este manda a correr el programa con la variable My aps a mi pareser lo manda a llamar
![image](https://user-images.githubusercontent.com/79875834/115074940-fae22980-9ebf-11eb-8ea6-841d0f6758bb.png)

en la clase podemos statewitget esta es la raiz de nuestra aplicacion.

![image](https://user-images.githubusercontent.com/79875834/115074965-033a6480-9ec0-11eb-895c-dbfd2fb42d02.png)

estos son objetos en el cual le estan dando atributos d color tamañño ets pero desde la libreria widget

![image](https://user-images.githubusercontent.com/79875834/115075011-0fbebd00-9ec0-11eb-867b-25e5a18ddda2.png)

comprovamos un ejemplo y modificamos algubos atributos de algunos objetos

![image](https://user-images.githubusercontent.com/79875834/115075080-29f89b00-9ec0-11eb-9796-bef881bc5ae5.png)

![image](https://user-images.githubusercontent.com/79875834/115075086-2d8c2200-9ec0-11eb-88a8-969408faf5fe.png)

![image](https://user-images.githubusercontent.com/79875834/115075101-341a9980-9ec0-11eb-9b3b-9ca83f65f1eb.png)

![image](https://user-images.githubusercontent.com/79875834/115075114-3977e400-9ec0-11eb-9fc5-ce53666d7bed.png)

![image](https://user-images.githubusercontent.com/79875834/115075145-40065b80-9ec0-11eb-90ca-46a4eddb3ea7.png)

#flutter camara_de_video

![image](https://user-images.githubusercontent.com/79875834/115075174-4ac0f080-9ec0-11eb-9f49-5f1fe1e8e8b6.png)

![image](https://user-images.githubusercontent.com/79875834/115075188-514f6800-9ec0-11eb-95ad-37b4e9489a21.png)

![image](https://user-images.githubusercontent.com/79875834/115075204-56acb280-9ec0-11eb-849e-13871db2f1fd.png)

Enlas pruevas que realise el celular estaba desconectado al omento de tomar una foto me marco error despues lo conecte y este me asedio omar una foto fue porque se perdio la interfaze

#flutter_tensorflow

![image](https://user-images.githubusercontent.com/79875834/115075234-64623800-9ec0-11eb-95c5-467bae2c27ea.png)

![image](https://user-images.githubusercontent.com/79875834/115075245-6a581900-9ec0-11eb-9a91-67e2dc72dc67.png)

![image](https://user-images.githubusercontent.com/79875834/115075258-6e843680-9ec0-11eb-8d03-f3f8ea5614e6.png)

![image](https://user-images.githubusercontent.com/79875834/115075274-73e18100-9ec0-11eb-90d6-ccb8f0a42750.png)

#flutter_componentes_master

![image](https://user-images.githubusercontent.com/79875834/115075307-81970680-9ec0-11eb-9008-ce0fd9896c87.png)

![image](https://user-images.githubusercontent.com/79875834/115075320-86f45100-9ec0-11eb-9e2d-013eef1872b9.png)

![image](https://user-images.githubusercontent.com/79875834/115075338-8b206e80-9ec0-11eb-89ac-ffbc50627552.png)

se esta iniciando la instalacion de la APK en nuestro celular

![image](https://user-images.githubusercontent.com/79875834/115075374-9a072100-9ec0-11eb-9080-c604ae1d85ff.png)

![image](https://user-images.githubusercontent.com/79875834/115075400-9ecbd500-9ec0-11eb-8704-3386e82d9ff7.png)

![image](https://user-images.githubusercontent.com/79875834/115075407-a25f5c00-9ec0-11eb-9d97-ad5cdf7432ab.png)

![image](https://user-images.githubusercontent.com/79875834/115075412-a55a4c80-9ec0-11eb-81ab-bcc8829f5c4b.png)


#app_Master
![image](https://user-images.githubusercontent.com/79875834/115075433-b014e180-9ec0-11eb-921c-2d4350c34cba.png)

![image](https://user-images.githubusercontent.com/79875834/115075446-b440ff00-9ec0-11eb-9406-79b193b0e6f4.png)

![image](https://user-images.githubusercontent.com/79875834/115075468-ba36e000-9ec0-11eb-91af-da6a62c952fe.png)

// class MyHomePage extends StatefulWidget { // MyHomePage({Key key, this.title}) : super(key: key); // final String title; // // @override // _MyHomePageState createState() => _MyHomePageState(); // } // // class _MyHomePageState extends State { // int _currentStep = 0; // BluetoothDevice device; // // void onStepContinue() async { // if (_currentStep == 0) { // setState(() { // _currentStep = 1; // }); // } // } // // void onStepCancel() { // if (_currentStep == 1) { // setState(() { // _currentStep = 0; // }); // } // } // // @override // Widget build(BuildContext context) { // List _steps = [ // Step( // title: Text('Connection'), // content: Container( // height: 500, // child: SelectBondedDevicePage( // onCahtPage: (BluetoothDevice device) { // Navigator.push( // context, // MaterialPageRoute( // builder: (context) { // return ChatPage(server: device); // }, // ), // ); // }, // ), // ), // state: StepState.editing, // isActive: true, // ), // Step( // title: Text('Led'), // content: Container( // // child: onCahtPage, // ), // ), // ]; // return Scaffold( // appBar: AppBar( // title: Text(widget.title), // ), // body: Stepper( // steps: _steps, // type: StepperType.horizontal, // currentStep: _currentStep, // onStepContinue: onStepContinue, // onStepCancel: onStepCancel, // ), // floatingActionButton: FloatingActionButton( // onPressed: () { // // // }, // tooltip: 'Increment', // child: Icon(Icons.search), // ), // This trailing comma makes auto-formatting nicer for build methods. // ); // } // }

![image](https://user-images.githubusercontent.com/79875834/115075529-d33f9100-9ec0-11eb-88d9-40d8a69fd322.png)

![image](https://user-images.githubusercontent.com/79875834/115075555-dd618f80-9ec0-11eb-81f2-87fefd1e580f.png)

aqui tenemos los APK instaladas en el celuarcelular







