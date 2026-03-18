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

# Server Metrics 2026-03-18 09:05:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 1466.1 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73734
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 1597
telemt_upstream_connect_attempt_total 49388
telemt_upstream_connect_success_total 48485
telemt_upstream_connect_fail_total 903
telemt_upstream_connect_attempts_per_request{bucket="1"} 49388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 903
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 505776
telemt_me_reconnect_success_total 293
telemt_me_reader_eof_total 195
telemt_me_idle_close_by_peer_total 193
telemt_me_route_drop_no_conn_total 7020
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13257
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 52
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 23
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 235
telemt_me_refill_failed_total 16480
telemt_me_writer_restored_same_endpoint_total 188
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 61281
telemt_user_connections_current{user="hello"} 1759
telemt_user_octets_from_client{user="hello"} 541508556 (516.42 MB)
telemt_user_octets_to_client{user="hello"} 9443494767 (8.79 GB)
telemt_user_msgs_from_client{user="hello"} 583493
telemt_user_msgs_to_client{user="hello"} 811764
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 320
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 1497.4 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145358
telemt_connections_bad_total 19754
telemt_handshake_timeouts_total 2883
telemt_upstream_connect_attempt_total 322
telemt_upstream_connect_success_total 322
telemt_upstream_connect_attempts_per_request{bucket="1"} 322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 207
telemt_me_reconnect_success_total 199
telemt_me_reader_eof_total 147
telemt_me_idle_close_by_peer_total 147
telemt_me_route_drop_no_conn_total 49788
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116505
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 504
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 368
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 168
telemt_me_writer_restored_same_endpoint_total 198
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 115843
telemt_user_connections_current{user="hello"} 3663
telemt_user_octets_from_client{user="hello"} 4714089948 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 33580956768 (31.27 GB)
telemt_user_unique_ips_current{user="hello"} 1047
telemt_user_unique_ips_recent_window{user="hello"} 659
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 1412.8 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127219
telemt_connections_bad_total 3976
telemt_handshake_timeouts_total 2387
telemt_upstream_connect_attempt_total 8655
telemt_upstream_connect_success_total 8655
telemt_upstream_connect_attempts_per_request{bucket="1"} 8655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 604566
telemt_me_reconnect_success_total 338
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 112970
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98886
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 125
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 278
telemt_me_refill_failed_total 19627
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 106995
telemt_user_connections_current{user="hello"} 2063
telemt_user_octets_from_client{user="hello"} 554837527 (529.13 MB)
telemt_user_octets_to_client{user="hello"} 16074749628 (14.97 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 536
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 1442.8 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125270
telemt_connections_bad_total 2542
telemt_handshake_timeouts_total 11363
telemt_upstream_connect_attempt_total 10929
telemt_upstream_connect_success_total 10852
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 10929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 793
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_reconnect_attempts_total 2809770
telemt_me_reconnect_success_total 457
telemt_me_reader_eof_total 405
telemt_me_idle_close_by_peer_total 405
telemt_me_route_drop_no_conn_total 38056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89609
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 183
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_me_writer_removed_unexpected_total 427
telemt_me_refill_failed_total 99529
telemt_me_writer_restored_same_endpoint_total 362
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_user_connections_total{user="hello"} 99855
telemt_user_connections_current{user="hello"} 3449
telemt_user_octets_from_client{user="hello"} 1060066362 (1010.96 MB)
telemt_user_octets_to_client{user="hello"} 22830969085 (21.26 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 862
telemt_user_unique_ips_recent_window{user="hello"} 534
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 1337.1 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98645
telemt_connections_bad_total 4268
telemt_handshake_timeouts_total 906
telemt_upstream_connect_attempt_total 10028
telemt_upstream_connect_success_total 10027
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982356
telemt_me_reconnect_success_total 408
telemt_me_reader_eof_total 329
telemt_me_idle_close_by_peer_total 329
telemt_me_route_drop_no_conn_total 26047
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72650
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 171
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_me_writer_removed_unexpected_total 351
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 293
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 82114
telemt_user_connections_current{user="hello"} 2769
telemt_user_octets_from_client{user="hello"} 1201709513 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 29911274749 (27.86 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 821
telemt_user_unique_ips_recent_window{user="hello"} 449
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 1222.2 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26809
telemt_connections_bad_total 5128
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 210
telemt_upstream_connect_success_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_me_reconnect_attempts_total 90
telemt_me_reconnect_success_total 90
telemt_me_reader_eof_total 55
telemt_me_idle_close_by_peer_total 55
telemt_me_route_drop_no_conn_total 7466
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20582
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 76
telemt_me_writer_restored_same_endpoint_total 82
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 20580
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 629253228 (600.10 MB)
telemt_user_octets_to_client{user="hello"} 4330229748 (4.03 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 1293.3 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77326
telemt_connections_bad_total 503
telemt_handshake_timeouts_total 1441
telemt_upstream_connect_attempt_total 245
telemt_upstream_connect_success_total 232
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 116
telemt_me_reconnect_success_total 108
telemt_me_reader_eof_total 65
telemt_me_idle_close_by_peer_total 65
telemt_me_route_drop_no_conn_total 90113
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71090
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 182
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 128
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_me_writer_removed_unexpected_total 90
telemt_me_writer_restored_same_endpoint_total 98
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 71034
telemt_user_connections_current{user="hello"} 2140
telemt_user_octets_from_client{user="hello"} 685371888 (653.62 MB)
telemt_user_octets_to_client{user="hello"} 24839077696 (23.13 GB)
telemt_user_unique_ips_current{user="hello"} 603
telemt_user_unique_ips_recent_window{user="hello"} 350
```