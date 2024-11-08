# Create-SIZE
fn main() {     const SIZE: usize = 5; // Задайте бажаний розмір ромба      // Верхня частина ромба     for i in 0..SIZE {         // Виведення пробілів         for _ in 0..(SIZE - i - 1) {             print!(" ");         }         // Виведення зірочок         for _ in 0..(2 * i + 1) {             print!("*");         }         
