# 🦀 Rust Compress

![Rust](https://img.shields.io/badge/Built%20With-Rust-black?style=for-the-badge\&logo=rust)
![Cargo](https://img.shields.io/badge/Cargo-Build%20Tool-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A simple and efficient file compression tool built in **Rust** using the **flate2** crate. This project compresses files into **GZIP (.gz)** format while displaying useful statistics such as original file size, compressed size, and execution time.

---

## 🚀 Features

* Compress files using GZIP compression
* Fast and lightweight implementation
* Command-line interface
* Displays source and compressed file sizes
* Measures compression time
* Built using safe and efficient Rust code

---

## 🛠️ Tech Stack

* Rust
* Cargo
* flate2

---

## 📂 Project Structure

```text
Rust-compress/
├── src/
│   └── main.rs
├── Cargo.toml
├── Cargo.lock
├── README.md
└── target/
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/tushar434434/Rust-compress.git
cd Rust-compress
```

Build the project:

```bash
cargo build
```

---

## ▶️ Usage

Place the file you want to compress inside the project directory and run:

```bash
cargo run -- <source_file> <target_file.gz>
```

### Example

```bash
cargo run -- test.txt test.gz
```

---

## 📊 Sample Output

```text
Source len: 30
Target len: 43
Elapsed: 762.3µs
```

---

## 📦 Dependencies

```toml
[dependencies]
flate2 = "1.0"
```

---

## 🧠 Concepts Learned

This project helped me understand:

* File handling in Rust
* Command-line arguments
* Working with external crates
* Buffered I/O
* Data compression
* Error handling
* Performance measurement using `Instant`

---

## 🔮 Future Improvements

* Add file decompression support
* Allow custom compression levels
* Compress entire directories
* Improve error messages
* Add progress indicators

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Tushar Kumar**

Second-year B.Tech student passionate about Rust, Backend Development, Data Structures & Algorithms, and Open Source.

GitHub: https://github.com/tushar434434
