# My title
## My title h2
### My title h3
#### My title h4
##### My title h5
###### My title h6

<!-- Este es un texto en italica -->
this is an *italic* text

<!-- Este es un texto en negrilla -->
this is an **strong** text

<!-- Este es un texto tachado -->
this is a ~~strikethrough~~ text

<!-- ul -->
 * apple
    * apple green
 * orange
    * orange yellow
 * manzana

 <!-- ol -->
 1. apple
    1. apple green
 2. orange
    * orange yellow
 3. manzana

 <!-- Enlaces -->

 [GitHub](https://github.com/DavidQRy)

 [Linkedin](https://Linkedin.com "Contactame en linkedin")

 > this is quote

 ---
 ___

 
 `Console.log()`
 ``` tsx
 export default function RootLayout({
  children,
}: Readonly<{
  children: React.ReactNode;
}>) {
  return (
    <html lang="en" 
    className="light dark">
      <body
        className={`${urbanist.variable} ${urbanist.variable} antialiased`}
      >
        <ThemeProvider
          attribute="class"
          defaultTheme="system"
          enableSystem
          disableTransitionOnChange
        >
          <NavBar />
          {children}
          <Footer />
        </ThemeProvider>
      </body>
    </html>
  );
}
 ```
 
  ``` python
def heloWord (name):
    print(f"Hello word, I am {name}")


myName = "David"

helloWord(myName)
 ```
 
  ``` html
 <h1>Hello word</h1>
 ```
 
|level |Lenguaje     |
|----- |-----        |
| low  | Assembly    |
| high | JavaScript   |
 

![visual studio code logo](./vscode.png "vscode logo")

<!-- GITHUB MARKDOWN -->
