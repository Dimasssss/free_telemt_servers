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

# Server Metrics 2026-03-17 03:36:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 31862.8 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165734
telemt_connections_bad_total 2411
telemt_handshake_timeouts_total 5624
telemt_upstream_connect_attempt_total 6848
telemt_upstream_connect_success_total 6807
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5223
telemt_me_reconnect_success_total 5207
telemt_me_reader_eof_total 5541
telemt_me_idle_close_by_peer_total 5541
telemt_me_route_drop_no_conn_total 53196
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150579
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 899
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 582
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 458
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5253
telemt_me_writer_restored_same_endpoint_total 5186
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 150388
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 2003237928 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 69020122528 (64.28 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 32114.2 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92929
telemt_connections_bad_total 1824
telemt_handshake_timeouts_total 3328
telemt_upstream_connect_attempt_total 9054
telemt_upstream_connect_success_total 8933
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 9054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_reconnect_attempts_total 8508
telemt_me_reconnect_success_total 7341
telemt_me_reader_eof_total 7732
telemt_me_idle_close_by_peer_total 7732
telemt_me_route_drop_no_conn_total 38602
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84059
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 216
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7448
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7325
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 84002
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 1177769952 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 38384147256 (35.75 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 31891.1 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60404
telemt_connections_bad_total 789
telemt_handshake_timeouts_total 2114
telemt_upstream_connect_attempt_total 8563
telemt_upstream_connect_success_total 8516
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 8563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4699
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 6940
telemt_me_reconnect_success_total 6900
telemt_me_reader_eof_total 7389
telemt_me_idle_close_by_peer_total 7389
telemt_me_route_drop_no_conn_total 19293
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51133
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6990
telemt_me_writer_restored_same_endpoint_total 6889
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 51118
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 5588420396 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 18203370104 (16.95 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 31949.7 (8h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94680
telemt_connections_bad_total 3413
telemt_handshake_timeouts_total 1795
telemt_upstream_connect_attempt_total 7388
telemt_upstream_connect_success_total 7324
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 7388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 5751
telemt_me_reconnect_success_total 5712
telemt_me_reader_eof_total 6073
telemt_me_idle_close_by_peer_total 6073
telemt_me_route_drop_no_conn_total 32423
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86808
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 159
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5791
telemt_me_writer_restored_same_endpoint_total 5705
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 86792
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 980783492 (935.35 MB)
telemt_user_octets_to_client{user="hello"} 41469291120 (38.62 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 31921.7 (8h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71283
telemt_connections_bad_total 16418
telemt_handshake_timeouts_total 1354
telemt_upstream_connect_attempt_total 9489
telemt_upstream_connect_success_total 9369
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 9489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 10012
telemt_me_reconnect_success_total 7762
telemt_me_reader_eof_total 8194
telemt_me_idle_close_by_peer_total 8194
telemt_me_route_drop_no_conn_total 20555
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51526
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7947
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 7754
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 51521
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 602265676 (574.37 MB)
telemt_user_octets_to_client{user="hello"} 22152191976 (20.63 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 32082.6 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184261
telemt_connections_bad_total 18372
telemt_handshake_timeouts_total 1174
telemt_upstream_connect_attempt_total 6668
telemt_upstream_connect_success_total 6631
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 5054
telemt_me_reconnect_success_total 5038
telemt_me_reader_eof_total 5400
telemt_me_idle_close_by_peer_total 5400
telemt_me_route_drop_no_conn_total 183262
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236712
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 144
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5109
telemt_me_writer_restored_same_endpoint_total 5028
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 158966
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 2473604776 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 127445829588 (118.69 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 20089.2 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 10136
telemt_upstream_connect_success_total 10136
telemt_upstream_connect_attempts_per_request{bucket="1"} 10136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 9115
telemt_me_reconnect_success_total 9065
telemt_me_reader_eof_total 9963
telemt_me_idle_close_by_peer_total 9963
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 9154
telemt_me_writer_restored_same_endpoint_total 9065
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```