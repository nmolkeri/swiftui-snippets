Alert 

```
@State private var showAlert = false
        
        var body: some View {
                Button("Tap me") {
                        showAlert = true
                }
                
                .alert("This is alert", isPresented: $showAlert) {
                        Button("ok") {}
                        Button("destroy", role: .destructive) {}
                        Button("cancel", role: .cancel) {}
                } message: {
                        Text("Please read this")
                }
        }
```
The state is automatically flipped to false. In built function of swift. 

![image](https://github.com/nmolkeri/swiftui-snippets/assets/10701840/0e372ac9-9c1b-4e1b-8cd5-fc775d4b3c64)

