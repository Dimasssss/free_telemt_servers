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

# Server Metrics 2026-03-19 00:10:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 8535.6 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99371
telemt_connections_bad_total 11044
telemt_connections_current 619
telemt_connections_me_current 619
telemt_handshake_timeouts_total 1047
telemt_upstream_connect_attempt_total 1652
telemt_upstream_connect_success_total 1625
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1175
telemt_me_reconnect_success_total 1172
telemt_me_reader_eof_total 1198
telemt_me_idle_close_by_peer_total 1198
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 31805
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82712
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 455
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 313
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1171
telemt_me_writer_restored_same_endpoint_total 1160
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 79956
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 757158900 (722.08 MB)
telemt_user_octets_to_client{user="hello"} 32160781372 (29.95 GB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 8539.7 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214912
telemt_connections_bad_total 16381
telemt_connections_current 1542
telemt_connections_me_current 1542
telemt_handshake_timeouts_total 1914
telemt_upstream_connect_attempt_total 1629
telemt_upstream_connect_success_total 1591
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 1629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 1135
telemt_me_reconnect_success_total 1134
telemt_me_reader_eof_total 1183
telemt_me_idle_close_by_peer_total 1183
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 66329
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184618
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 758
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 509
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1154
telemt_me_writer_restored_same_endpoint_total 1123
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 184693
telemt_user_connections_current{user="hello"} 1542
telemt_user_octets_from_client{user="hello"} 10531562992 (9.81 GB)
telemt_user_octets_to_client{user="hello"} 69739394048 (64.95 GB)
telemt_user_unique_ips_current{user="hello"} 625
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 8538.1 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167688
telemt_connections_bad_total 25551
telemt_connections_current 1127
telemt_connections_me_current 1127
telemt_handshake_timeouts_total 4615
telemt_upstream_connect_attempt_total 1673
telemt_upstream_connect_success_total 1673
telemt_upstream_connect_attempts_per_request{bucket="1"} 1673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1217
telemt_me_reconnect_success_total 1214
telemt_me_reader_eof_total 1263
telemt_me_idle_close_by_peer_total 1263
telemt_me_route_drop_no_conn_total 56269
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132457
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 576
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 351
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1231
telemt_me_writer_restored_same_endpoint_total 1198
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 132459
telemt_user_connections_current{user="hello"} 1127
telemt_user_octets_from_client{user="hello"} 1807018480 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 78891687904 (73.47 GB)
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 8590.1 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177627
telemt_connections_bad_total 25313
telemt_connections_current 950
telemt_connections_me_current 950
telemt_handshake_timeouts_total 3363
telemt_upstream_connect_attempt_total 1599
telemt_upstream_connect_success_total 1599
telemt_upstream_connect_attempts_per_request{bucket="1"} 1599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1145
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 1182
telemt_me_idle_close_by_peer_total 1182
telemt_me_route_drop_no_conn_total 66908
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137522
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 353
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1154
telemt_me_writer_restored_same_endpoint_total 1116
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 137448
telemt_user_connections_current{user="hello"} 950
telemt_user_octets_from_client{user="hello"} 1527656812 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 51017848324 (47.51 GB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 8533.5 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183932
telemt_connections_bad_total 8103
telemt_connections_current 1159
telemt_connections_me_current 1159
telemt_handshake_timeouts_total 6460
telemt_upstream_connect_attempt_total 1591
telemt_upstream_connect_success_total 1580
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1124
telemt_me_reconnect_success_total 1118
telemt_me_reader_eof_total 1157
telemt_me_idle_close_by_peer_total 1157
telemt_me_route_drop_no_conn_total 59673
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143680
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 601
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1122
telemt_me_writer_restored_same_endpoint_total 1094
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 143620
telemt_user_connections_current{user="hello"} 1159
telemt_user_octets_from_client{user="hello"} 1894562284 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 89974778140 (83.80 GB)
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 8545.1 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45219
telemt_connections_bad_total 7727
telemt_connections_current 398
telemt_connections_me_current 398
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 2643
telemt_upstream_connect_success_total 2564
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 2643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_reconnect_attempts_total 3937
telemt_me_reconnect_success_total 2111
telemt_me_reader_eof_total 2187
telemt_me_idle_close_by_peer_total 2187
telemt_me_route_drop_no_conn_total 16296
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36297
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2146
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2081
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 36298
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 423917672 (404.28 MB)
telemt_user_octets_to_client{user="hello"} 25246341300 (23.51 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 8535.9 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136065
telemt_connections_bad_total 17492
telemt_connections_current 1084
telemt_connections_me_current 1084
telemt_handshake_timeouts_total 4921
telemt_upstream_connect_attempt_total 1732
telemt_upstream_connect_success_total 1732
telemt_upstream_connect_attempts_per_request{bucket="1"} 1732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1276
telemt_me_reconnect_success_total 1273
telemt_me_reader_eof_total 1323
telemt_me_idle_close_by_peer_total 1323
telemt_me_route_drop_no_conn_total 40954
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111085
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 764
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1287
telemt_me_writer_restored_same_endpoint_total 1258
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 111110
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 1081052472 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 58843619536 (54.80 GB)
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 104
```