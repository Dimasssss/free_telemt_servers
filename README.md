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

# Server Metrics 2026-03-19 13:03:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 1274.2 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52995
telemt_connections_bad_total 2323
telemt_connections_current 1752
telemt_connections_me_current 1752
telemt_handshake_timeouts_total 1568
telemt_upstream_connect_attempt_total 196
telemt_upstream_connect_success_total 177
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 78
telemt_me_reconnect_success_total 62
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 23104
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45753
telemt_me_writer_pick_total{mode="p2c",result="full"} 54
telemt_me_writer_pick_total{mode="p2c",result="closed"} 152
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 206
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 72
telemt_me_writer_restored_same_endpoint_total 51
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 220
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 45346
telemt_user_connections_current{user="hello"} 1752
telemt_user_octets_from_client{user="hello"} 760617316 (725.38 MB)
telemt_user_octets_to_client{user="hello"} 13408197748 (12.49 GB)
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 349
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 1184.1 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172469
telemt_connections_bad_total 2411
telemt_connections_current 3732
telemt_connections_me_current 3732
telemt_handshake_timeouts_total 1158
telemt_upstream_connect_attempt_total 1595
telemt_upstream_connect_success_total 1588
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 263
telemt_me_reconnect_success_total 257
telemt_me_reader_eof_total 205
telemt_me_idle_close_by_peer_total 205
telemt_me_route_drop_no_conn_total 231560
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158290
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 395
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 276
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 229
telemt_me_writer_restored_same_endpoint_total 202
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_user_connections_total{user="hello"} 159166
telemt_user_connections_current{user="hello"} 3732
telemt_user_octets_from_client{user="hello"} 1026063658 (978.53 MB)
telemt_user_octets_to_client{user="hello"} 24649725250 (22.96 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1291
telemt_user_unique_ips_recent_window{user="hello"} 589
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 1149.4 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114570
telemt_connections_bad_total 17578
telemt_connections_current 3403
telemt_connections_me_current 3403
telemt_handshake_timeouts_total 1531
telemt_upstream_connect_attempt_total 243
telemt_upstream_connect_success_total 237
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 130
telemt_me_reconnect_success_total 127
telemt_me_reader_eof_total 84
telemt_me_idle_close_by_peer_total 84
telemt_me_route_drop_no_conn_total 51496
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87076
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_restored_same_endpoint_total 124
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 86931
telemt_user_connections_current{user="hello"} 3403
telemt_user_octets_from_client{user="hello"} 1223079536 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 19260822228 (17.94 GB)
telemt_user_unique_ips_current{user="hello"} 1009
telemt_user_unique_ips_recent_window{user="hello"} 594
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 54872.8 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3671232
telemt_connections_bad_total 738473
telemt_connections_current 3693
telemt_connections_me_current 3693
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 72248
telemt_upstream_connect_attempt_total 61521
telemt_upstream_connect_success_total 59040
telemt_upstream_connect_fail_total 2481
telemt_upstream_connect_attempts_per_request{bucket="1"} 61521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2481
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70184
telemt_me_reconnect_success_total 7133
telemt_me_reader_eof_total 7454
telemt_me_idle_close_by_peer_total 7451
telemt_me_route_drop_no_conn_total 1632711
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2457503
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10522
telemt_desync_full_logged_total 3277
telemt_desync_suppressed_total 7245
telemt_desync_frames_bucket_total{bucket="1_2"} 1905
telemt_desync_frames_bucket_total{bucket="3_10"} 4468
telemt_desync_frames_bucket_total{bucket="gt_10"} 4149
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7253
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7109
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 2506374
telemt_user_connections_current{user="hello"} 3693
telemt_user_octets_from_client{user="hello"} 40204439183 (37.44 GB)
telemt_user_octets_to_client{user="hello"} 912704071200 (850.02 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1152
telemt_user_unique_ips_recent_window{user="hello"} 623
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 1114.3 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32535
telemt_connections_bad_total 764
telemt_connections_current 879
telemt_connections_me_current 879
telemt_handshake_timeouts_total 206
telemt_upstream_connect_attempt_total 218
telemt_upstream_connect_success_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 71
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_reconnect_attempts_total 107
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 39
telemt_me_idle_close_by_peer_total 39
telemt_me_route_drop_no_conn_total 31602
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29978
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 63
telemt_me_writer_restored_same_endpoint_total 93
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 145
telemt_me_async_recovery_trigger_total 928
telemt_user_connections_total{user="hello"} 30548
telemt_user_connections_current{user="hello"} 879
telemt_user_octets_from_client{user="hello"} 320494644 (305.65 MB)
telemt_user_octets_to_client{user="hello"} 4992442156 (4.65 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 1114.2 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81148
telemt_connections_bad_total 7285
telemt_connections_current 3482
telemt_connections_me_current 3482
telemt_handshake_timeouts_total 574
telemt_upstream_connect_attempt_total 190
telemt_upstream_connect_success_total 187
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 79
telemt_me_reconnect_success_total 75
telemt_me_reader_eof_total 55
telemt_me_idle_close_by_peer_total 55
telemt_me_route_drop_no_conn_total 22533
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69704
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 282
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 77
telemt_me_writer_restored_same_endpoint_total 58
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 69691
telemt_user_connections_current{user="hello"} 3482
telemt_user_octets_from_client{user="hello"} 730032124 (696.21 MB)
telemt_user_octets_to_client{user="hello"} 25914338764 (24.13 GB)
telemt_user_unique_ips_current{user="hello"} 1094
telemt_user_unique_ips_recent_window{user="hello"} 561
```