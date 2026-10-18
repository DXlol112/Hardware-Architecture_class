# Архитектура аппаратных средств

В репозитории собраны конспекты занятий, домашние и контрольные работы по предмету **«Архитектура аппаратных средств»**.

## Оглавление

| Занятие | Конспект | Домашняя работа |
| --- | --- | --- |
| 1 | [Компьютерные основы: представление данных](lesson_01/class/computer-fundamentals.md) | [Таблицы истинности логических выражений](lesson_01/hw/hw_01.md) |
| 2 | [Логические элементы и сумматор](lesson_02/class/logic-gates-and-adder.md) | [Преобразование логических схем и формул](lesson_02/hw/hw_02.md) |
| 3 | [Процессор: теория](lesson_03/class/processor-theory.md) | — |
| 4 | [Рабочий цикл процессора](lesson_04/class/processor-instruction-cycle.md) | — |
| 5 | [Память и управление памятью](lesson_05/class/memory-and-memory-management.md) | [Сегментно-страничная архитектура](lesson_05/hw/hw.md) |
| 6 | — | [HDD, SSD и оперативная память](lesson_06/hw/hw.md) |

## Контрольные работы

- [Контрольная работа № 1](control-test/control-test-01.md)

## Структура

```text
├── .github/
│   ├── assets/
│   │   ├── lesson_01/
│   │   │   └── class/
│   │   │       ├── bits-slide-07-memory.png
│   │   │       ├── bits-slide-10-byte-order.png
│   │   │       ├── bits-slide-17-bitwise-operations.png
│   │   │       ├── bits-slide-21-shifts.png
│   │   │       ├── bits-slide-32-signed-unsigned.png
│   │   │       ├── bits-slide-36-sign-extension.png
│   │   │       └── bits-slide-40-addition.png
│   │   ├── lesson_02/
│   │   │   ├── class/
│   │   │   │   ├── and-gate.png
│   │   │   │   ├── circuit-building-steps.png
│   │   │   │   ├── logic-elements.png
│   │   │   │   ├── multi-bit-adder.png
│   │   │   │   ├── not-gate.png
│   │   │   │   ├── one-bit-adder.png
│   │   │   │   ├── or-gate.png
│   │   │   │   ├── trigger.png
│   │   │   │   └── xor-gate.png
│   │   │   └── hw/
│   │   │       ├── scheme_01.png
│   │   │       ├── scheme_02.png
│   │   │       ├── scheme_03.png
│   │   │       └── scheme_04.png
│   │   ├── lesson_03/
│   │   │   ├── 8086-address-space.png
│   │   │   ├── 8086-flags-register.png
│   │   │   ├── 8086-instruction-formats.png
│   │   │   ├── 8086-memory-segments.png
│   │   │   ├── accumulator-architecture.png
│   │   │   ├── alu-circuit-diagram.png
│   │   │   ├── alu-operation-selection.png
│   │   │   ├── arithmetic-right-shift.png
│   │   │   ├── bus-datapath-types.png
│   │   │   ├── call-and-return-stack.png
│   │   │   ├── control-unit-model.png
│   │   │   ├── eight-bit-alu.png
│   │   │   ├── full-two-operand-instruction-format.png
│   │   │   ├── gate-and-test-microinstruction-formats.png
│   │   │   ├── hardwired-control-unit.png
│   │   │   ├── ibm-pc-memory-map.png
│   │   │   ├── instruction-pipelining.png
│   │   │   ├── instruction-set-architecture-classification.png
│   │   │   ├── intel-8086-architecture.png
│   │   │   ├── microprocessor-external-signals.png
│   │   │   ├── microprogram-memory-addressing.png
│   │   │   ├── microprogrammed-control-unit.png
│   │   │   ├── multiplexer-and-strobes.png
│   │   │   ├── offset-and-physical-address-calculation.png
│   │   │   ├── prefixes-and-addressing-byte.png
│   │   │   ├── processor-structure.png
│   │   │   ├── register-based-hardware-stack.png
│   │   │   ├── register-data-transfer.png
│   │   │   ├── register-file.png
│   │   │   ├── rotate-operation-circuits.png
│   │   │   ├── segment-address-and-offset.png
│   │   │   ├── stack-implementation-types.png
│   │   │   ├── subroutine-call-and-return.png
│   │   │   ├── subroutine-disassembly.png
│   │   │   ├── three-bus-datapath.png
│   │   │   ├── three-bus-processor-control-gates.png
│   │   │   ├── three-internal-bus-processor.png
│   │   │   ├── transfer-shift-and-add.png
│   │   │   ├── von-neumann-datapath.png
│   │   │   └── x86-stack-frame.png
│   │   ├── lesson_04/
│   │   │   ├── addition-result-in-accumulator.png
│   │   │   ├── alu-operation-execution.png
│   │   │   ├── alu-status-and-interrupt-flags.png
│   │   │   ├── binary-number-representation.png
│   │   │   ├── branch-mask-and-result-status.png
│   │   │   ├── branch-mask-check.png
│   │   │   ├── conditional-branch-circuit.png
│   │   │   ├── control-signal-sequence.png
│   │   │   ├── control-unit-signals.png
│   │   │   ├── first-operand-fetch.png
│   │   │   ├── instruction-fetch.png
│   │   │   ├── km1816ve51-arithmetic-instructions.png
│   │   │   ├── masked-conditional-branch-algorithm.png
│   │   │   ├── memory-read-and-write.png
│   │   │   ├── operands-in-alu-registers.png
│   │   │   ├── processor-external-pins.png
│   │   │   ├── processor-memory-system-bus.png
│   │   │   ├── processor-set-and-reset.png
│   │   │   ├── program-counter-advance.png
│   │   │   ├── result-status-and-flags-save.png
│   │   │   ├── result-write-to-memory.png
│   │   │   ├── second-operand-fetch.png
│   │   │   ├── simplified-processor-and-memory-diagram.png
│   │   │   ├── stack-and-interrupt-vector-table.png
│   │   │   ├── sum-write-and-next-instruction.png
│   │   │   ├── three-byte-instruction-load.png
│   │   │   └── two-address-instruction-format.png
│   │   └── lesson_05/
│   │       ├── cache-structure.png
│   │       ├── cmos-and-battery.png
│   │       ├── dynamic-memory-mapping.png
│   │       ├── dynamic-partitions.png
│   │       ├── fixed-partitions.png
│   │       ├── hard-disk-drive.png
│   │       ├── memory-allocation-methods.png
│   │       ├── memory-compaction.png
│   │       ├── memory-hierarchy.png
│   │       ├── overlay-structure.png
│   │       ├── page-address-translation.png
│   │       ├── process-page-tables.png
│   │       ├── ram-modules.png
│   │       ├── rom-chip.png
│   │       ├── segment-address-translation.png
│   │       ├── segmented-paging-diagram.png
│   │       ├── segmented-paging.png
│   │       ├── shared-segments.png
│   │       ├── single-program-memory-layout.png
│   │       ├── storage-device-types.png
│   │       ├── system-bus-data-transfer.png
│   │       ├── tape-drive.png
│   │       ├── usb-flash-drive.png
│   │       ├── virtual-address-translation.png
│   │       └── von-neumann-architecture.png
│   └── src/
│       └── lesson_01/
│           └── hw.py
├── .gitignore
├── control-test/
│   └── control-test-01.md
├── lesson_01/
│   ├── class/
│   │   └── computer-fundamentals.md
│   └── hw/
│       └── hw_01.md
├── lesson_02/
│   ├── class/
│   │   └── logic-gates-and-adder.md
│   └── hw/
│       └── hw_02.md
├── lesson_03/
│   └── class/
│       └── processor-theory.md
├── lesson_04/
│   └── class/
│       └── processor-instruction-cycle.md
├── lesson_05/
│   ├── class/
│   │   └── memory-and-memory-management.md
│   └── hw/
│       └── hw.md
├── lesson_06/
│   └── hw/
│       └── hw.md
├── LICENSE.md
└── README.md
```
