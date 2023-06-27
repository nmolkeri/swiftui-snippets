#Button and Images snippets

```
Button("Delete Item", role: .destructive) {}
```
![image](https://github.com/nmolkeri/swiftui-snippets/assets/10701840/ad2a0dd9-c2e7-4f74-a22f-f259eb31dd0b)

```
                        Button("Button1") {}
                                .buttonStyle(.bordered)
                        Button("Button2") {}
                                .buttonStyle(.borderedProminent)
                        Button("Button3", role: .destructive) {}
                                .buttonStyle(.bordered)
                        Button("Button4", role: .destructive) {}
                                .buttonStyle(.borderedProminent)
```

![image](https://github.com/nmolkeri/swiftui-snippets/assets/10701840/19dd1b1c-14b8-46e9-9408-d2c3a19edda9)

```
Button{} label: {
                                Text("Tap me!!")
                                        .padding()
                                        .foregroundColor(.white)
                                        .background(.red)
                        }
```
![image](https://github.com/nmolkeri/swiftui-snippets/assets/10701840/0b39aba4-17cd-4620-8f4b-8b9b9d2fcc43)

```
                        Button{} label: {
                                Label("Edit", systemImage: "pencil")
                        }
```
![image](https://github.com/nmolkeri/swiftui-snippets/assets/10701840/23dabd8c-6e62-4efb-a6b2-5dd348b44404)
