![Workspace](https://github.com/Honojerame/gif/blob/main/242390524-0c7eb6ed-663b-4ce4-bfbd-18239a38ba1b.gif)

# Hi, I'm Precious Onojerame

Aspiring computer engineer focused on processor architecture, RTL design, and
the hardware behind intelligent systems.

I'm a Computer Science and Electronics Engineering Technology double-major at
Eastern New Mexico University and a **Module Equipment Technician at Intel**
in Rio Rancho, New Mexico. I enjoy building systems I can run, inspect, test,
and improve, from semiconductor-fab simulations to processor pipelines.

## My story

My path toward computer engineering combines hands-on technical work with
software, electronics, and machine learning. I began working in Intel's
semiconductor manufacturing environment through Kelly Services, supporting
equipment maintenance and troubleshooting.

On **August 31, 2026, I joined Intel directly as a Module Equipment Technician**.
My work involves preventive maintenance, troubleshooting, repair, and equipment
certification in semiconductor manufacturing. That experience keeps reliability,
root-cause analysis, and the physical behavior of hardware central to how I
approach engineering.

Alongside my work and studies, I'm developing a deeper foundation in digital
design, computer architecture, and verification. My goal is to contribute to
CPU/GPU architecture and AI accelerator design, connecting my experience with
physical systems to the logic and data movement inside computing hardware.

## Featured RTL & architecture projects

Four independent educational RTL studies with architecture guides, interface
contracts, testbenches, reference models, and documented scope.

### 1. [Four-Core RV32I Cluster](https://github.com/Honojerame/Honojerame.github.io/tree/main/engineering/projects/01_rv32_cluster)

Four five-stage integer pipelines with forwarding, load-use interlocks, branch
flushes, precise terminal traps, and a locked round-robin shared-memory arbiter.
An independent instruction model checked **25,668 retirement events** across
**32 program/core configurations**, with complete final-memory comparison.

`SystemVerilog` `RV32I` `Pipelining` `Differential Verification`

[Case study](https://honojerame.github.io/project-rv32-cluster.html) ·
[Architecture](https://github.com/Honojerame/Honojerame.github.io/blob/main/engineering/projects/01_rv32_cluster/docs/architecture.md) ·
[Verification](https://github.com/Honojerame/Honojerame.github.io/blob/main/engineering/projects/01_rv32_cluster/docs/verification.md)

### 2. [INT8 Systolic Accelerator](https://github.com/Honojerame/Honojerame.github.io/tree/main/engineering/projects/02_systolic_int8)

An output-stationary MAC array with signed INT8 operands, INT32 accumulation,
skewed operand delivery, tail masking, and backpressured output. Tests compared
**1,344 matrix elements** across **48 configurations** using 2×2, 4×4, and 8×8
arrays, with measured compute utilization.

`SystemVerilog` `Systolic Arrays` `INT8 / INT32` `Accelerator Dataflow`

[Case study](https://honojerame.github.io/project-systolic-int8.html) ·
[Architecture](https://github.com/Honojerame/Honojerame.github.io/blob/main/engineering/projects/02_systolic_int8/docs/architecture.md) ·
[Verification](https://github.com/Honojerame/Honojerame.github.io/blob/main/engineering/projects/02_systolic_int8/docs/verification.md)

### 3. [GPU-Style Warp Memory](https://github.com/Honojerame/Honojerame.github.io/tree/main/engineering/projects/03_warp_memory)

A global-load coalescer groups lane accesses into tagged 32-byte sectors and
gathers out-of-order replies. A separate banked scratchpad handles broadcasts,
conflict replay, and deterministic same-word stores. Verification covered
**948 operations** and **18,096 lane values** at 8 and 32 lanes.

`SystemVerilog` `SIMT Memory` `Coalescing` `Banked Storage`

[Case study](https://honojerame.github.io/project-warp-memory.html) ·
[Architecture](https://github.com/Honojerame/Honojerame.github.io/blob/main/engineering/projects/03_warp_memory/docs/architecture.md) ·
[Verification](https://github.com/Honojerame/Honojerame.github.io/blob/main/engineering/projects/03_warp_memory/docs/verification.md)

### 4. [Mesh Network-on-Chip](https://github.com/Honojerame/Honojerame.github.io/tree/main/engineering/projects/04_mesh_noc)

A buffered mesh of five-port routers with deterministic XY routing, per-output
round-robin arbitration, and stable grants under backpressure. Packet
scoreboards checked **33,120 packets** across **48 traffic experiments** on
2×2, 3×2, and 3×3 meshes.

`SystemVerilog` `XY Routing` `FIFO Design` `On-Chip Interconnect`

[Case study](https://honojerame.github.io/project-mesh-noc.html) ·
[Architecture](https://github.com/Honojerame/Honojerame.github.io/blob/main/engineering/projects/04_mesh_noc/docs/architecture.md) ·
[Verification](https://github.com/Honojerame/Honojerame.github.io/blob/main/engineering/projects/04_mesh_noc/docs/verification.md)

Across the collection: **1,076 simulation cases/operations**, with Verilator
lint and Yosys generic synthesis checks for five top levels. These are
simulation-verified educational designs; physical implementation and
compliance certification are outside the published scope.

[Complete source & documentation](https://github.com/Honojerame/Honojerame.github.io/tree/main/engineering) ·
[Measured results](https://github.com/Honojerame/Honojerame.github.io/blob/main/engineering/docs/results.md) ·
[Engineering notebook](https://honojerame.github.io/engineering.html)

## Other projects

### 5. [AMHS FOUP Digital Twin](https://github.com/Honojerame/amhs-foup-digital-twin)

A real-time simulation of semiconductor-fab material handling. It models FOUP
dispatch, multi-vehicle overhead hoist transport, acceleration-limited servo
drives, hoist actuators, encoder feedback, microcontroller-style state machines,
safety interlocks, and E-stop recovery.

The browser control room animates the plant and exposes live velocity, controller
state, throughput, queue activity, time scaling, and fault injection. The repo
also includes automated tests, GitHub Actions CI, and complete system drawings.

`Python` `Robotics` `Embedded Controls` `Drives` `Actuators` `Digital Twin` `HMI`

### 6. [Prisca SPY Predictor](https://github.com/Honojerame/prisca-spy-predictor)

Collaborative ML pipeline using financial-news sentiment and historical market
data to forecast next-day SPY opening price with FinBERT and tree-based models.

### 7. [Solar Energy Forecasting](https://github.com/Honojerame/AI-Solar_Power_Prediciton)

Machine-learning models for forecasting solar power output from historical and
meteorological features.

### 8. [Bus Ticket Management System](https://github.com/Honojerame/CS234_BusTicketManagementSystem)

Java Swing desktop application for drivers, passengers, ticket history, and
administrative workflows using object-oriented design.

## Technical focus

| Area | Current focus |
| --- | --- |
| RTL & architecture | SystemVerilog, Verilog/VHDL, RV32I, pipelining, systolic arrays, memory systems, NoCs |
| Verification | Icarus Verilog, Verilator, Yosys, Python reference models, self-checking testbenches, GitHub Actions |
| Embedded & controls | C, C++, Arduino, sensors, actuators, FSMs, PID concepts |
| Software | Python, Java, JavaScript, Git, Linux, Docker, REST, CI/CD |
| AI & data | NumPy, pandas, scikit-learn, TensorFlow, NLP |
| Physical systems | Semiconductor manufacturing, equipment troubleshooting, robotics, digital twins |

## Currently building toward

- CPU/GPU architecture and AI accelerator design
- Stronger foundations in digital design, microarchitecture, and verification
- Reliable hardware/software interfaces grounded in real physical systems

## Connect

- [Portfolio](https://honojerame.github.io)
- [LinkedIn](https://www.linkedin.com/in/precious-onojerame-880498183/)
- [Email](mailto:preciousonoj@gmail.com)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Honojerame&layout=compact&theme=tokyonight)
