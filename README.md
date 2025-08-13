# Atomic-
Jsx
const sab = new SharedArrayBuffer(16);
const int32Array = new Int32Array(sab);

Atomics.store(int32Array, 0, 10);
console.log(Atomics.load(int32Array, 0)); // 10

Atomics.add(int32Array, 0, 20);
console.log(Atomics.load(int32Array, 0)); // 30
const sab = new SharedArrayBuffer(16);
const int32Array = new Int32Array(sab);

Atomics.store(int32Array, 0, 10);
console.log(Atomics.load(int32Array, 0)); // 10

Atomics.add(int32Array, 0, 20);
console.log(Atomics.load(int32Array, 0)); // 30
