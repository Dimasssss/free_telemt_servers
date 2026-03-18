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

# Server Metrics 2026-03-18 09:15:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 2076.8 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99824
telemt_connections_bad_total 236
telemt_handshake_timeouts_total 2089
telemt_upstream_connect_attempt_total 63338
telemt_upstream_connect_success_total 62427
telemt_upstream_connect_fail_total 911
telemt_upstream_connect_attempts_per_request{bucket="1"} 63338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 911
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 505845
telemt_me_reconnect_success_total 329
telemt_me_reader_eof_total 232
telemt_me_idle_close_by_peer_total 230
telemt_me_route_drop_no_conn_total 9984
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22797
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 68
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 273
telemt_me_refill_failed_total 16481
telemt_me_writer_restored_same_endpoint_total 224
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 84681
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 934362420 (891.08 MB)
telemt_user_octets_to_client{user="hello"} 14967615781 (13.94 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 2108.5 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202206
telemt_connections_bad_total 30221
telemt_handshake_timeouts_total 4320
telemt_upstream_connect_attempt_total 434
telemt_upstream_connect_success_total 434
telemt_upstream_connect_attempts_per_request{bucket="1"} 434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 275
telemt_me_reconnect_success_total 266
telemt_me_reader_eof_total 220
telemt_me_idle_close_by_peer_total 220
telemt_me_route_drop_no_conn_total 66785
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155824
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 507
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 237
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 155133
telemt_user_connections_current{user="hello"} 3474
telemt_user_octets_from_client{user="hello"} 5361594492 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 50350320172 (46.89 GB)
telemt_user_unique_ips_current{user="hello"} 1026
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 2053.5 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179170
telemt_connections_bad_total 4113
telemt_handshake_timeouts_total 22182
telemt_upstream_connect_attempt_total 11094
telemt_upstream_connect_success_total 11011
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 11094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_reconnect_attempts_total 2810398
telemt_me_reconnect_success_total 572
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_route_drop_no_conn_total 62222
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127909
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_me_writer_removed_unexpected_total 558
telemt_me_refill_failed_total 99545
telemt_me_writer_restored_same_endpoint_total 477
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_user_connections_total{user="hello"} 138128
telemt_user_connections_current{user="hello"} 3186
telemt_user_octets_from_client{user="hello"} 1524522990 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 33482968269 (31.18 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 845
telemt_user_unique_ips_recent_window{user="hello"} 423
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 1948.3 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137744
telemt_connections_bad_total 5833
telemt_handshake_timeouts_total 1181
telemt_upstream_connect_attempt_total 10136
telemt_upstream_connect_success_total 10135
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982420
telemt_me_reconnect_success_total 472
telemt_me_reader_eof_total 396
telemt_me_idle_close_by_peer_total 396
telemt_me_route_drop_no_conn_total 40165
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105859
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 276
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 415
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 357
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 115278
telemt_user_connections_current{user="hello"} 2839
telemt_user_octets_from_client{user="hello"} 1623598097 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 44119086393 (41.09 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 818
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 1833.8 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38534
telemt_connections_bad_total 6078
telemt_handshake_timeouts_total 199
telemt_upstream_connect_attempt_total 273
telemt_upstream_connect_success_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 101
telemt_me_reconnect_attempts_total 148
telemt_me_reconnect_success_total 147
telemt_me_reader_eof_total 112
telemt_me_idle_close_by_peer_total 112
telemt_me_route_drop_no_conn_total 10601
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30600
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 133
telemt_me_writer_restored_same_endpoint_total 139
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 30597
telemt_user_connections_current{user="hello"} 975
telemt_user_octets_from_client{user="hello"} 750536128 (715.77 MB)
telemt_user_octets_to_client{user="hello"} 6561070388 (6.11 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 1904.4 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102246
telemt_connections_bad_total 570
telemt_handshake_timeouts_total 1701
telemt_upstream_connect_attempt_total 313
telemt_upstream_connect_success_total 299
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 153
telemt_me_reconnect_success_total 144
telemt_me_reader_eof_total 103
telemt_me_idle_close_by_peer_total 103
telemt_me_route_drop_no_conn_total 99137
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94339
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_me_writer_removed_unexpected_total 128
telemt_me_writer_restored_same_endpoint_total 134
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 94257
telemt_user_connections_current{user="hello"} 1888
telemt_user_octets_from_client{user="hello"} 1034129040 (986.22 MB)
telemt_user_octets_to_client{user="hello"} 35578994804 (33.14 GB)
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 290
```