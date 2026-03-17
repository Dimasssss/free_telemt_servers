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

# Server Metrics 2026-03-17 05:59:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 40424.8 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230223
telemt_connections_bad_total 3317
telemt_handshake_timeouts_total 7540
telemt_upstream_connect_attempt_total 8467
telemt_upstream_connect_success_total 8422
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6448
telemt_me_reconnect_success_total 6424
telemt_me_reader_eof_total 6834
telemt_me_idle_close_by_peer_total 6834
telemt_me_route_drop_no_conn_total 71294
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207869
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1402
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 935
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 710
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6488
telemt_me_writer_restored_same_endpoint_total 6403
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 207663
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 2855656756 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 92131439724 (85.80 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 40676.1 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132316
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 10442
telemt_upstream_connect_attempt_total 11242
telemt_upstream_connect_success_total 11096
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 11242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_reconnect_attempts_total 10240
telemt_me_reconnect_success_total 9065
telemt_me_reader_eof_total 9588
telemt_me_idle_close_by_peer_total 9588
telemt_me_route_drop_no_conn_total 50253
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114805
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9184
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9049
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 114816
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 1429031708 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 49315121640 (45.93 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 40452.8 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79335
telemt_connections_bad_total 1108
telemt_handshake_timeouts_total 2621
telemt_upstream_connect_attempt_total 10878
telemt_upstream_connect_success_total 10822
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 10878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5980
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8853
telemt_me_reconnect_success_total 8804
telemt_me_reader_eof_total 9417
telemt_me_idle_close_by_peer_total 9417
telemt_me_route_drop_no_conn_total 26461
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68159
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 46
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8911
telemt_me_writer_restored_same_endpoint_total 8793
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 68143
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 6051227292 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 22347816344 (20.81 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 40511.5 (11h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136931
telemt_connections_bad_total 3780
telemt_handshake_timeouts_total 5500
telemt_upstream_connect_attempt_total 9192
telemt_upstream_connect_success_total 9116
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 7115
telemt_me_reconnect_success_total 7061
telemt_me_reader_eof_total 7508
telemt_me_idle_close_by_peer_total 7508
telemt_me_route_drop_no_conn_total 45739
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123623
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7163
telemt_me_writer_restored_same_endpoint_total 7054
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 123640
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 1357109430 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 59699569569 (55.60 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 40483.5 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104095
telemt_connections_bad_total 30042
telemt_handshake_timeouts_total 2035
telemt_upstream_connect_attempt_total 12017
telemt_upstream_connect_success_total 11861
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 12017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_reconnect_attempts_total 12010
telemt_me_reconnect_success_total 9747
telemt_me_reader_eof_total 10298
telemt_me_idle_close_by_peer_total 10298
telemt_me_route_drop_no_conn_total 26919
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69209
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 9944
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9739
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 69306
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 755538191 (720.54 MB)
telemt_user_octets_to_client{user="hello"} 30037616486 (27.97 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 40644.4 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247420
telemt_connections_bad_total 29675
telemt_handshake_timeouts_total 2032
telemt_upstream_connect_attempt_total 8327
telemt_upstream_connect_success_total 8282
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6271
telemt_me_reconnect_success_total 6242
telemt_me_reader_eof_total 6695
telemt_me_idle_close_by_peer_total 6695
telemt_me_route_drop_no_conn_total 205991
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284231
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 243
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6334
telemt_me_writer_restored_same_endpoint_total 6232
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 206483
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 3135506132 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 149617497568 (139.34 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 28651.0 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 690
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 14136
telemt_upstream_connect_success_total 14136
telemt_upstream_connect_attempts_per_request{bucket="1"} 14136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 12724
telemt_me_reconnect_success_total 12653
telemt_me_reader_eof_total 13887
telemt_me_idle_close_by_peer_total 13887
telemt_me_route_drop_no_conn_total 71
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 12769
telemt_me_writer_restored_same_endpoint_total 12653
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 492
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 179916620 (171.58 MB)
telemt_user_octets_to_client{user="hello"} 6355730692 (5.92 GB)
telemt_user_unique_ips_current{user="hello"} 6
```