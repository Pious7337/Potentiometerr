\begin{lstlisting}[caption=Arduino Potentiometer Code]
const int potPin = A4;

void setup() {
  Serial.begin(115200);
}

void loop() {
  int potValue = analogRead(potPin);
  Serial.print("Potentiometer Value: ");
  Serial.println(potValue);
  delay(1000);
}
\end{lstlisting}
