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

# Server Metrics 2026-03-12 18:53:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 40772.6 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206699
telemt_connections_bad_total 2610
telemt_handshake_timeouts_total 4963
telemt_upstream_connect_attempt_total 10410
telemt_upstream_connect_success_total 10365
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 10410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1423
telemt_me_reconnect_attempts_total 11712
telemt_me_reconnect_success_total 8254
telemt_me_reader_eof_total 8751
telemt_me_idle_close_by_peer_total 8750
telemt_me_route_drop_no_conn_total 61636
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173510
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 636
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 8460
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8238
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 173469
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 3064775248 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 75845605220 (70.64 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 40665.1 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90940
telemt_connections_bad_total 480
telemt_handshake_timeouts_total 703
telemt_upstream_connect_attempt_total 21445
telemt_upstream_connect_success_total 21177
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 21445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 43881
telemt_me_reconnect_success_total 9121
telemt_me_reader_eof_total 10379
telemt_me_idle_close_by_peer_total 10379
telemt_me_route_drop_no_conn_total 35461
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76561
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 11
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10279
telemt_me_refill_failed_total 1085
telemt_me_writer_restored_same_endpoint_total 9106
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1158
telemt_user_connections_total{user="hello"} 86519
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 955381029 (911.12 MB)
telemt_user_octets_to_client{user="hello"} 25334205044 (23.59 GB)
telemt_user_msgs_from_client{user="hello"} 160954
telemt_user_msgs_to_client{user="hello"} 1347514
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 40628.6 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117486
telemt_connections_bad_total 1513
telemt_handshake_timeouts_total 2137
telemt_upstream_connect_attempt_total 11416
telemt_upstream_connect_success_total 11416
telemt_upstream_connect_attempts_per_request{bucket="1"} 11416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 10418
telemt_me_reconnect_success_total 9285
telemt_me_reader_eof_total 9848
telemt_me_idle_close_by_peer_total 9848
telemt_me_route_drop_no_conn_total 44186
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109121
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 9408
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 9265
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 109093
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 2441716288 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 55051358420 (51.27 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 40604.5 (11h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169563
telemt_connections_bad_total 13108
telemt_handshake_timeouts_total 1242
telemt_upstream_connect_attempt_total 22029
telemt_upstream_connect_success_total 12426
telemt_upstream_connect_fail_total 9603
telemt_upstream_connect_attempts_per_request{bucket="1"} 22029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9603
telemt_me_keepalive_timeout_total 2418
telemt_me_reconnect_attempts_total 38654
telemt_me_reconnect_success_total 7473
telemt_me_reader_eof_total 8644
telemt_me_idle_close_by_peer_total 8637
telemt_me_route_drop_no_conn_total 57635
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135271
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 464
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 8580
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 7463
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1107
telemt_user_connections_total{user="hello"} 138029
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 2539520066 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 55576568921 (51.76 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 40561.0 (11h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258706
telemt_connections_bad_total 2130
telemt_handshake_timeouts_total 2149
telemt_upstream_connect_attempt_total 8594
telemt_upstream_connect_success_total 8549
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 8593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 470
telemt_me_reconnect_attempts_total 10093
telemt_me_reconnect_success_total 6489
telemt_me_reader_eof_total 6912
telemt_me_idle_close_by_peer_total 6911
telemt_me_route_drop_no_conn_total 120046
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257167
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6683
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6482
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 246205
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 4285088240 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 115312877372 (107.39 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 57
```