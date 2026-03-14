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

# Server Metrics 2026-03-14 14:20:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 3851.2 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19656
telemt_connections_bad_total 1115
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 953
telemt_upstream_connect_success_total 953
telemt_upstream_connect_attempts_per_request{bucket="1"} 953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 707
telemt_me_reconnect_success_total 695
telemt_me_reader_eof_total 714
telemt_me_idle_close_by_peer_total 714
telemt_me_route_drop_no_conn_total 9135
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18032
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 708
telemt_me_writer_restored_same_endpoint_total 677
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 17973
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 319839640 (305.02 MB)
telemt_user_octets_to_client{user="hello"} 7376357636 (6.87 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 3849.1 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9113
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 442
telemt_upstream_connect_attempt_total 999
telemt_upstream_connect_success_total 977
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 748
telemt_me_reconnect_success_total 724
telemt_me_reader_eof_total 742
telemt_me_idle_close_by_peer_total 742
telemt_me_route_drop_no_conn_total 3863
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8387
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 740
telemt_me_writer_restored_same_endpoint_total 719
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 8370
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 93918100 (89.57 MB)
telemt_user_octets_to_client{user="hello"} 2982290464 (2.78 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 3853.3 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8942
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 170
telemt_upstream_connect_attempt_total 2385
telemt_upstream_connect_success_total 2368
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 94424
telemt_me_reconnect_success_total 1798
telemt_me_reader_eof_total 1853
telemt_me_idle_close_by_peer_total 1853
telemt_me_route_drop_no_conn_total 3147
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7886
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 1870
telemt_me_refill_failed_total 3006
telemt_me_writer_restored_same_endpoint_total 1760
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 8196
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 278041141 (265.16 MB)
telemt_user_octets_to_client{user="hello"} 4277647582 (3.98 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 3858.3 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12427
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 88
telemt_upstream_connect_attempt_total 943
telemt_upstream_connect_success_total 939
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 696
telemt_me_reconnect_success_total 690
telemt_me_reader_eof_total 687
telemt_me_idle_close_by_peer_total 687
telemt_me_route_drop_no_conn_total 6451
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11820
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 159
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 686
telemt_me_writer_restored_same_endpoint_total 688
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_user_connections_total{user="hello"} 11705
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 156097560 (148.87 MB)
telemt_user_octets_to_client{user="hello"} 3648600140 (3.40 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 3851.5 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8603
telemt_connections_bad_total 836
telemt_handshake_timeouts_total 83
telemt_upstream_connect_attempt_total 1102
telemt_upstream_connect_success_total 1085
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 1102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 606
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 3302
telemt_me_reconnect_success_total 830
telemt_me_reader_eof_total 882
telemt_me_idle_close_by_peer_total 882
telemt_me_route_drop_no_conn_total 3071
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7250
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 901
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 826
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 7246
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 56395056 (53.78 MB)
telemt_user_octets_to_client{user="hello"} 1566901056 (1.46 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 3851.2 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29378
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 149
telemt_upstream_connect_attempt_total 898
telemt_upstream_connect_success_total 870
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 637
telemt_me_reconnect_success_total 612
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 14248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27234
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 609
telemt_me_writer_restored_same_endpoint_total 608
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 27155
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 562495576 (536.44 MB)
telemt_user_octets_to_client{user="hello"} 11347726708 (10.57 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 72
```