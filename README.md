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

# Server Metrics 2026-03-18 09:00:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 1160.6 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58985
telemt_connections_bad_total 193
telemt_handshake_timeouts_total 1271
telemt_upstream_connect_attempt_total 35584
telemt_upstream_connect_success_total 34869
telemt_upstream_connect_fail_total 715
telemt_upstream_connect_attempts_per_request{bucket="1"} 35584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 715
telemt_me_reconnect_attempts_total 414487
telemt_me_reconnect_success_total 281
telemt_me_reader_eof_total 168
telemt_me_idle_close_by_peer_total 166
telemt_me_route_drop_no_conn_total 5142
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13188
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
telemt_me_writer_removed_unexpected_total 202
telemt_me_refill_failed_total 13629
telemt_me_writer_restored_same_endpoint_total 178
telemt_me_writer_restored_fallback_total 103
telemt_me_async_recovery_trigger_total 10397
telemt_user_connections_total{user="hello"} 47609
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 419946045 (400.49 MB)
telemt_user_octets_to_client{user="hello"} 7443244719 (6.93 GB)
telemt_user_msgs_from_client{user="hello"} 417974
telemt_user_msgs_to_client{user="hello"} 591695
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 1191.8 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113471
telemt_connections_bad_total 15291
telemt_handshake_timeouts_total 2121
telemt_upstream_connect_attempt_total 294
telemt_upstream_connect_success_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 77
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 179
telemt_me_reconnect_success_total 173
telemt_me_reader_eof_total 122
telemt_me_idle_close_by_peer_total 122
telemt_me_route_drop_no_conn_total 34578
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91128
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 350
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 142
telemt_me_writer_restored_same_endpoint_total 172
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 90793
telemt_user_connections_current{user="hello"} 3518
telemt_user_octets_from_client{user="hello"} 3702621956 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 25256909344 (23.52 GB)
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 563
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 1137.1 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96423
telemt_connections_bad_total 2030
telemt_handshake_timeouts_total 6405
telemt_upstream_connect_attempt_total 10879
telemt_upstream_connect_success_total 10802
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 10879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_reconnect_attempts_total 2809720
telemt_me_reconnect_success_total 407
telemt_me_reader_eof_total 355
telemt_me_idle_close_by_peer_total 355
telemt_me_route_drop_no_conn_total 26868
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68283
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_me_writer_removed_unexpected_total 377
telemt_me_refill_failed_total 99529
telemt_me_writer_restored_same_endpoint_total 312
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_user_connections_total{user="hello"} 78552
telemt_user_connections_current{user="hello"} 2978
telemt_user_octets_from_client{user="hello"} 782100246 (745.87 MB)
telemt_user_octets_to_client{user="hello"} 17464284137 (16.26 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 805
telemt_user_unique_ips_recent_window{user="hello"} 449
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 1032.0 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77362
telemt_connections_bad_total 3171
telemt_handshake_timeouts_total 680
telemt_upstream_connect_attempt_total 9951
telemt_upstream_connect_success_total 9950
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982222
telemt_me_reconnect_success_total 343
telemt_me_reader_eof_total 260
telemt_me_idle_close_by_peer_total 260
telemt_me_route_drop_no_conn_total 18299
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54567
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_me_writer_removed_unexpected_total 282
telemt_me_refill_failed_total 107151
telemt_me_writer_restored_same_endpoint_total 228
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 64036
telemt_user_connections_current{user="hello"} 2660
telemt_user_octets_from_client{user="hello"} 1030751205 (983.00 MB)
telemt_user_octets_to_client{user="hello"} 23077491753 (21.49 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 458
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 917.7 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20411
telemt_connections_bad_total 4502
telemt_handshake_timeouts_total 81
telemt_upstream_connect_attempt_total 128
telemt_upstream_connect_success_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_me_reconnect_attempts_total 59
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 23
telemt_me_idle_close_by_peer_total 23
telemt_me_route_drop_no_conn_total 4918
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14980
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_writer_removed_unexpected_total 45
telemt_me_writer_restored_same_endpoint_total 51
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 14979
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 564400168 (538.25 MB)
telemt_user_octets_to_client{user="hello"} 2817120836 (2.62 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 987.7 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46491
telemt_connections_bad_total 415
telemt_handshake_timeouts_total 1241
telemt_upstream_connect_attempt_total 157
telemt_upstream_connect_success_total 144
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 62
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 19718
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41797
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 152
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_me_writer_removed_unexpected_total 40
telemt_me_writer_restored_same_endpoint_total 49
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 41745
telemt_user_connections_current{user="hello"} 1974
telemt_user_octets_from_client{user="hello"} 470154492 (448.37 MB)
telemt_user_octets_to_client{user="hello"} 19659072968 (18.31 GB)
telemt_user_unique_ips_current{user="hello"} 595
telemt_user_unique_ips_recent_window{user="hello"} 333
```