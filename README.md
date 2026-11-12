路线B：运动预测与瞄准

环境：Rust 1.98.1

运行命令：
cargo run --locked 
（平移+自旋）
cargo run --locked -- --config scenarios/stationary.json
cargo run --locked -- --config scenarios/spinning.json
cargo run --locked -- --config scenarios/moving.json





完全按照作业下的四步实现，考虑了各种误差和error。
结果在各个情境下都是80/80命中