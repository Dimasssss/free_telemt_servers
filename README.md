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

# Server Metrics 2026-03-12 12:48:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18899.8 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100724
telemt_connections_bad_total 541
telemt_handshake_timeouts_total 3535
telemt_upstream_connect_attempt_total 4569
telemt_upstream_connect_success_total 4548
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 3604
telemt_me_reconnect_success_total 3582
telemt_me_reader_eof_total 3744
telemt_me_idle_close_by_peer_total 3743
telemt_me_route_drop_no_conn_total 28008
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90157
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 414
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 254
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3606
telemt_me_writer_restored_same_endpoint_total 3566
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 90124
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 1250986108 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 31658930348 (29.48 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 18793.6 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40592
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 321
telemt_upstream_connect_attempt_total 5590
telemt_upstream_connect_success_total 5449
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 5590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 20324
telemt_me_reconnect_success_total 4501
telemt_me_reader_eof_total 5038
telemt_me_idle_close_by_peer_total 5038
telemt_me_route_drop_no_conn_total 17382
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38617
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 5011
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 4486
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 38617
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 461642472 (440.26 MB)
telemt_user_octets_to_client{user="hello"} 10370095076 (9.66 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 18757.1 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55011
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 524
telemt_upstream_connect_attempt_total 5140
telemt_upstream_connect_success_total 5140
telemt_upstream_connect_attempts_per_request{bucket="1"} 5140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 4196
telemt_me_reconnect_success_total 4165
telemt_me_reader_eof_total 4388
telemt_me_idle_close_by_peer_total 4388
telemt_me_route_drop_no_conn_total 19179
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51826
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4187
telemt_me_writer_restored_same_endpoint_total 4145
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 51809
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 1742128012 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 32532554232 (30.30 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 18732.8 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70295
telemt_connections_bad_total 1082
telemt_handshake_timeouts_total 325
telemt_upstream_connect_attempt_total 5035
telemt_upstream_connect_success_total 4911
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 5035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 190
telemt_me_reconnect_attempts_total 10489
telemt_me_reconnect_success_total 3944
telemt_me_reader_eof_total 4274
telemt_me_idle_close_by_peer_total 4274
telemt_me_route_drop_no_conn_total 23696
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64441
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 127
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4198
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3936
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 64442
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 1107928624 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 30935147964 (28.81 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18702.3 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39450
telemt_connections_bad_total 3543
telemt_handshake_timeouts_total 641
telemt_upstream_connect_attempt_total 8277
telemt_upstream_connect_success_total 8051
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 8277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 23154
telemt_me_reconnect_success_total 3595
telemt_me_reader_eof_total 4203
telemt_me_idle_close_by_peer_total 4203
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 11262
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30769
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 396
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4227
telemt_me_refill_failed_total 612
telemt_me_writer_restored_same_endpoint_total 3578
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 34261
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 240529971 (229.39 MB)
telemt_user_octets_to_client{user="hello"} 8536495570 (7.95 GB)
telemt_user_msgs_from_client{user="hello"} 40344
telemt_user_msgs_to_client{user="hello"} 149043
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 18689.2 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105970
telemt_connections_bad_total 763
telemt_handshake_timeouts_total 940
telemt_upstream_connect_attempt_total 3773
telemt_upstream_connect_success_total 3753
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 3773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 2824
telemt_me_reconnect_success_total 2797
telemt_me_reader_eof_total 2941
telemt_me_idle_close_by_peer_total 2941
telemt_me_route_drop_no_conn_total 43669
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100780
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 209
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2833
telemt_me_writer_restored_same_endpoint_total 2790
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 100747
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 2501385780 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 47633031464 (44.36 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 57
```