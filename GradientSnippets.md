#Gradient Snippets

```
RadialGradient(gradient: Gradient(colors: [.red, .blue]),
                                                        center: .center,
                                                        startRadius: 20,
                                                        endRadius: 200)
                .ignoresSafeArea()
```
![image](https://github.com/nmolkeri/swiftui-snippets/assets/10701840/1f44740a-516f-4742-a58d-2089a3521c81)

```
LinearGradient(gradient: Gradient(colors: [.red, .blue]),
                               startPoint: .top,
                               endPoint: .bottom)
                .ignoresSafeArea()
```

![image](https://github.com/nmolkeri/swiftui-snippets/assets/10701840/7a917887-932e-403f-9fa6-5831b85e487f)

```
LinearGradient(gradient: Gradient(stops: [
                        Gradient.Stop(color: .red, location: 0.45),
                        Gradient.Stop(color: .blue, location: 0.55)
                ]),
                               startPoint: .top,
                               endPoint: .bottom)
                .ignoresSafeArea()
```

![image](https://github.com/nmolkeri/swiftui-snippets/assets/10701840/999e2770-eb2f-4540-b102-c12b26b8f4c5)

```
AngularGradient(gradient: Gradient(colors: [
                        .red,
                        .yellow,
                        .green,
                        .blue,
                        .purple,
                        .red]),
                                center: .center)
                .ignoresSafeArea()
```
![image](https://github.com/nmolkeri/swiftui-snippets/assets/10701840/27ca0508-6d4d-48a3-8687-da69c33d75b0)


