---
layout: session
permalink: /sessions/:name

type: workshop

title: Rust and eBPF

desc: >
    **2-day workshop**
    <br>
    In 2019, there's Kubernetes everywhere, and developers have become used to just dropping a container to get our apps running,
    then quickly forgetting them until something breaks again.
    The convenience is hard to question.
    But how do we know what happens in the meantime? This workshop will introduce the basics of modern Linux monitoring using Rust and eBPF.

    You will learn how to write eBPF modules that run inside the kernel to intercept syscalls with Kprobes,
    filter and monitor network traffic using XDP, and copy packets into user space using socket filters.

    We'll use InGRAINd, Red Sift's eBPF platform that lets you write all the code in Rust,
    and compile everything into a single binary, and pop it onto a server without any special setup.

    Bring your own workload, containers, VMs, cluster, mainframe, or Raspberry Pi.

socialTwitterCardType: summary_large_image
socialImageSrc: /assets/social/rust-and-ebpf.png
description: "Filter & monitor network traffic, intercept syscalls, all with the help of Rust and eBPF"

public: true
---