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

# Server Metrics 2026-03-17 07:30:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 45920.4 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300248
telemt_connections_bad_total 3529
telemt_handshake_timeouts_total 9600
telemt_upstream_connect_attempt_total 9437
telemt_upstream_connect_success_total 9386
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7149
telemt_me_reconnect_success_total 7122
telemt_me_reader_eof_total 7581
telemt_me_idle_close_by_peer_total 7581
telemt_me_route_drop_no_conn_total 91455
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269656
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2035
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 1435
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 1034
telemt_desync_frames_bucket_total{bucket="gt_10"} 568
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7195
telemt_me_writer_restored_same_endpoint_total 7101
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 269429
telemt_user_connections_current{user="hello"} 865
telemt_user_octets_from_client{user="hello"} 3542616828 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 117744318772 (109.66 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 46171.8 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169477
telemt_connections_bad_total 2349
telemt_handshake_timeouts_total 11846
telemt_upstream_connect_attempt_total 12636
telemt_upstream_connect_success_total 12472
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 12636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_reconnect_attempts_total 11354
telemt_me_reconnect_success_total 10171
telemt_me_reader_eof_total 10742
telemt_me_idle_close_by_peer_total 10742
telemt_me_route_drop_no_conn_total 61147
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146419
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 381
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 245
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10303
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10155
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 146458
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 1798611772 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 60764179148 (56.59 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 45947.9 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101272
telemt_connections_bad_total 3066
telemt_handshake_timeouts_total 4287
telemt_upstream_connect_attempt_total 12042
telemt_upstream_connect_success_total 11979
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 12042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9734
telemt_me_reconnect_success_total 9679
telemt_me_reader_eof_total 10361
telemt_me_idle_close_by_peer_total 10361
telemt_me_route_drop_no_conn_total 32804
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85328
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 87
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9798
telemt_me_writer_restored_same_endpoint_total 9668
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 85284
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 6336019032 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 26389075376 (24.58 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 46007.3 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197333
telemt_connections_bad_total 5835
telemt_handshake_timeouts_total 9947
telemt_upstream_connect_attempt_total 10507
telemt_upstream_connect_success_total 10418
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 10507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 8118
telemt_me_reconnect_success_total 8052
telemt_me_reader_eof_total 8548
telemt_me_idle_close_by_peer_total 8548
telemt_me_route_drop_no_conn_total 59374
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166355
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 326
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8168
telemt_me_writer_restored_same_endpoint_total 8044
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 166362
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 1752423370 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 76111115897 (70.88 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 45979.1 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131458
telemt_connections_bad_total 38381
telemt_handshake_timeouts_total 2442
telemt_upstream_connect_attempt_total 13942
telemt_upstream_connect_success_total 13763
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 13942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 14617
telemt_me_reconnect_success_total 11355
telemt_me_reader_eof_total 11999
telemt_me_idle_close_by_peer_total 11999
telemt_me_route_drop_no_conn_total 34152
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87024
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 89
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11600
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11347
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 87065
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 908101903 (866.03 MB)
telemt_user_octets_to_client{user="hello"} 40911087338 (38.10 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 46140.4 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310817
telemt_connections_bad_total 42166
telemt_handshake_timeouts_total 2711
telemt_upstream_connect_attempt_total 9549
telemt_upstream_connect_success_total 9499
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 8437
telemt_me_reconnect_success_total 7186
telemt_me_reader_eof_total 7708
telemt_me_idle_close_by_peer_total 7708
telemt_me_route_drop_no_conn_total 236368
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 331943
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 358
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7329
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 7172
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 253873
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 3650407548 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 162357259308 (151.21 GB)
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 34146.6 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1611
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 17029
telemt_upstream_connect_success_total 17028
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15356
telemt_me_reconnect_success_total 15268
telemt_me_reader_eof_total 16697
telemt_me_idle_close_by_peer_total 16697
telemt_me_route_drop_no_conn_total 219
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1400
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 15405
telemt_me_writer_restored_same_endpoint_total 15268
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 1400
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 217308132 (207.24 MB)
telemt_user_octets_to_client{user="hello"} 15498481976 (14.43 GB)
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```