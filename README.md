# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 13:17:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 66735.4 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 655499
telemt_connections_bad_total 5198
telemt_handshake_timeouts_total 20186
telemt_upstream_connect_attempt_total 16565
telemt_upstream_connect_success_total 16113
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 16565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 14822
telemt_me_reconnect_success_total 10466
telemt_me_reader_eof_total 11158
telemt_me_idle_close_by_peer_total 11157
telemt_me_route_drop_no_conn_total 217893
telemt_me_route_drop_channel_closed_total 67
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592770
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4379
telemt_desync_full_logged_total 1201
telemt_desync_suppressed_total 3178
telemt_desync_frames_bucket_total{bucket="1_2"} 1256
telemt_desync_frames_bucket_total{bucket="3_10"} 1806
telemt_desync_frames_bucket_total{bucket="gt_10"} 1317
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10753
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 10444
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 594662
telemt_user_connections_current{user="hello"} 1024
telemt_user_octets_from_client{user="hello"} 8722392999 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 210741698607 (196.27 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 66987.0 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395189
telemt_connections_bad_total 23998
telemt_handshake_timeouts_total 20618
telemt_upstream_connect_attempt_total 16861
telemt_upstream_connect_success_total 16588
telemt_upstream_connect_fail_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 16861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 273
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 27604
telemt_me_reconnect_success_total 13214
telemt_me_reader_eof_total 14242
telemt_me_idle_close_by_peer_total 14242
telemt_me_route_drop_no_conn_total 163221
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330113
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1282
telemt_desync_full_logged_total 417
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 573
telemt_desync_frames_bucket_total{bucket="gt_10"} 425
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13825
telemt_me_refill_failed_total 446
telemt_me_writer_restored_same_endpoint_total 13198
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 330057
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 3680203852 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 114769443488 (106.89 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 66762.6 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215469
telemt_connections_bad_total 7758
telemt_handshake_timeouts_total 16621
telemt_upstream_connect_attempt_total 17599
telemt_upstream_connect_success_total 17509
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 17599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 16038
telemt_me_reconnect_success_total 14121
telemt_me_reader_eof_total 15048
telemt_me_idle_close_by_peer_total 15048
telemt_me_route_drop_no_conn_total 74775
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179749
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 699
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14379
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 14110
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 179637
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 15239491684 (14.19 GB)
telemt_user_octets_to_client{user="hello"} 50491097060 (47.02 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 66822.1 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493253
telemt_connections_bad_total 7896
telemt_handshake_timeouts_total 12647
telemt_upstream_connect_attempt_total 16096
telemt_upstream_connect_success_total 15950
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 16096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 16148
telemt_me_reconnect_success_total 11548
telemt_me_reader_eof_total 12351
telemt_me_idle_close_by_peer_total 12351
telemt_me_route_drop_no_conn_total 142509
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416524
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1482
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 364
telemt_desync_frames_bucket_total{bucket="3_10"} 664
telemt_desync_frames_bucket_total{bucket="gt_10"} 454
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11895
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 11539
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 417392
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 5312094678 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 143184010431 (133.35 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 66793.9 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247564
telemt_connections_bad_total 56067
telemt_handshake_timeouts_total 3229
telemt_upstream_connect_attempt_total 19357
telemt_upstream_connect_success_total 19107
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 19357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 32260
telemt_me_reconnect_success_total 15620
telemt_me_reader_eof_total 16776
telemt_me_idle_close_by_peer_total 16776
telemt_me_route_drop_no_conn_total 65261
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179264
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1069
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 536
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16345
telemt_me_refill_failed_total 517
telemt_me_writer_restored_same_endpoint_total 15612
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 179278
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 2336932323 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 69636631966 (64.85 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 66955.2 (18h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 587862
telemt_connections_bad_total 53237
telemt_handshake_timeouts_total 5862
telemt_upstream_connect_attempt_total 13589
telemt_upstream_connect_success_total 13517
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 13589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6803
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 15094
telemt_me_reconnect_success_total 10160
telemt_me_reader_eof_total 10956
telemt_me_idle_close_by_peer_total 10956
telemt_me_route_drop_no_conn_total 393006
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588310
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 835
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10472
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 10146
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 498059
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 7274023044 (6.77 GB)
telemt_user_octets_to_client{user="hello"} 236814211640 (220.55 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 14722.0 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11446
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 8302
telemt_upstream_connect_success_total 8231
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 8302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 12646
telemt_me_reconnect_success_total 7313
telemt_me_reader_eof_total 7672
telemt_me_idle_close_by_peer_total 7672
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 4066
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11052
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 7551
telemt_me_refill_failed_total 165
telemt_me_writer_restored_same_endpoint_total 7299
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 11155
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 314629993 (300.05 MB)
telemt_user_octets_to_client{user="hello"} 21455464270 (19.98 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 7
```