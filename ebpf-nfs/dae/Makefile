# SPDX-License-Identifier: (GPL-2.0 OR BSD-2-Clause)

include ../Makefile

XDP_TARGETS := tproxy
# XDP_FUNCTION := tproxy_lan_egress

target: BPF_CFLAGS += -D$(PROG)
# dae_target: XDP_C := ./programs/tail_called/events/syscall_dispatched_events/$(NAME).bpf.c
# sys_symbex: XDP_TARGETS := $(NAME).bpf

target: xdp-target
# dae_symbex: symbex