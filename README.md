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

# Server Metrics 2026-03-17 03:31:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 31557.7 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164238
telemt_connections_bad_total 2399
telemt_handshake_timeouts_total 5591
telemt_upstream_connect_attempt_total 6753
telemt_upstream_connect_success_total 6713
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5152
telemt_me_reconnect_success_total 5136
telemt_me_reader_eof_total 5463
telemt_me_idle_close_by_peer_total 5463
telemt_me_route_drop_no_conn_total 52633
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149152
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 886
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 575
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5182
telemt_me_writer_restored_same_endpoint_total 5115
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 148961
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 1990412624 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 68535207404 (63.83 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 31808.9 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91969
telemt_connections_bad_total 1694
telemt_handshake_timeouts_total 3270
telemt_upstream_connect_attempt_total 8928
telemt_upstream_connect_success_total 8807
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 8928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_reconnect_attempts_total 8382
telemt_me_reconnect_success_total 7215
telemt_me_reader_eof_total 7606
telemt_me_idle_close_by_peer_total 7606
telemt_me_route_drop_no_conn_total 38362
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83308
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 208
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7322
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7199
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 83251
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 1172200300 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 38034508228 (35.42 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 31585.3 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59839
telemt_connections_bad_total 789
telemt_handshake_timeouts_total 2088
telemt_upstream_connect_attempt_total 8484
telemt_upstream_connect_success_total 8437
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 8484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 6866
telemt_me_reconnect_success_total 6827
telemt_me_reader_eof_total 7299
telemt_me_idle_close_by_peer_total 7299
telemt_me_route_drop_no_conn_total 19036
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50615
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6915
telemt_me_writer_restored_same_endpoint_total 6816
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 50601
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 5584590704 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 18152751084 (16.91 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 31644.3 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93885
telemt_connections_bad_total 3408
telemt_handshake_timeouts_total 1794
telemt_upstream_connect_attempt_total 7316
telemt_upstream_connect_success_total 7252
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 7316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 5679
telemt_me_reconnect_success_total 5640
telemt_me_reader_eof_total 5996
telemt_me_idle_close_by_peer_total 5996
telemt_me_route_drop_no_conn_total 32162
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86031
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
telemt_me_writer_removed_unexpected_total 5719
telemt_me_writer_restored_same_endpoint_total 5633
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 86015
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 977471656 (932.19 MB)
telemt_user_octets_to_client{user="hello"} 41296184960 (38.46 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 31616.3 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70873
telemt_connections_bad_total 16346
telemt_handshake_timeouts_total 1327
telemt_upstream_connect_attempt_total 9392
telemt_upstream_connect_success_total 9272
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 9392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 9915
telemt_me_reconnect_success_total 7665
telemt_me_reader_eof_total 8081
telemt_me_idle_close_by_peer_total 8081
telemt_me_route_drop_no_conn_total 20317
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51212
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
telemt_me_writer_removed_unexpected_total 7849
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 7657
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 51207
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 599992428 (572.20 MB)
telemt_user_octets_to_client{user="hello"} 22057358416 (20.54 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 31777.5 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181939
telemt_connections_bad_total 17488
telemt_handshake_timeouts_total 1170
telemt_upstream_connect_attempt_total 6625
telemt_upstream_connect_success_total 6588
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 5011
telemt_me_reconnect_success_total 4994
telemt_me_reader_eof_total 5357
telemt_me_idle_close_by_peer_total 5357
telemt_me_route_drop_no_conn_total 182709
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235320
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5066
telemt_me_writer_restored_same_endpoint_total 4984
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 157574
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 2461687244 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 125835907260 (117.19 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 19783.7 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 9960
telemt_upstream_connect_success_total 9960
telemt_upstream_connect_attempts_per_request{bucket="1"} 9960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 8982
telemt_me_reconnect_success_total 8933
telemt_me_reader_eof_total 9788
telemt_me_idle_close_by_peer_total 9788
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9020
telemt_me_writer_restored_same_endpoint_total 8933
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```