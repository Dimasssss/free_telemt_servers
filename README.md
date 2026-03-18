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

# Server Metrics 2026-03-18 08:50:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 549.5 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33359
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 462
telemt_upstream_connect_attempt_total 18714
telemt_upstream_connect_success_total 18410
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 18713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_reconnect_attempts_total 413906
telemt_me_reconnect_success_total 236
telemt_me_reader_eof_total 112
telemt_me_idle_close_by_peer_total 110
telemt_me_route_drop_no_conn_total 2935
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7470
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 52
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 7
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_me_writer_removed_unexpected_total 136
telemt_me_refill_failed_total 13613
telemt_me_writer_restored_same_endpoint_total 133
telemt_me_writer_restored_fallback_total 103
telemt_me_async_recovery_trigger_total 10397
telemt_user_connections_total{user="hello"} 25538
telemt_user_connections_current{user="hello"} 1506
telemt_user_octets_from_client{user="hello"} 178156897 (169.90 MB)
telemt_user_octets_to_client{user="hello"} 3811958681 (3.55 GB)
telemt_user_msgs_from_client{user="hello"} 178716
telemt_user_msgs_to_client{user="hello"} 252411
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 580.4 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60219
telemt_connections_bad_total 6341
telemt_handshake_timeouts_total 864
telemt_upstream_connect_attempt_total 194
telemt_upstream_connect_success_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 122
telemt_me_reconnect_success_total 119
telemt_me_reader_eof_total 62
telemt_me_idle_close_by_peer_total 62
telemt_me_route_drop_no_conn_total 19488
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50121
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 164
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_me_writer_removed_unexpected_total 83
telemt_me_writer_restored_same_endpoint_total 118
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 49757
telemt_user_connections_current{user="hello"} 3221
telemt_user_octets_from_client{user="hello"} 424227808 (404.58 MB)
telemt_user_octets_to_client{user="hello"} 11598039628 (10.80 GB)
telemt_user_unique_ips_current{user="hello"} 974
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 495.5 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42678
telemt_connections_bad_total 863
telemt_handshake_timeouts_total 910
telemt_upstream_connect_attempt_total 8517
telemt_upstream_connect_success_total 8517
telemt_upstream_connect_attempts_per_request{bucket="1"} 8517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 603673
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 136
telemt_me_idle_close_by_peer_total 136
telemt_me_route_drop_no_conn_total 12212
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27958
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_me_writer_removed_unexpected_total 159
telemt_me_refill_failed_total 19602
telemt_me_writer_restored_same_endpoint_total 210
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14847
telemt_user_connections_total{user="hello"} 36073
telemt_user_connections_current{user="hello"} 2038
telemt_user_octets_from_client{user="hello"} 180393963 (172.04 MB)
telemt_user_octets_to_client{user="hello"} 8080179004 (7.53 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 609
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 525.5 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51380
telemt_connections_bad_total 982
telemt_handshake_timeouts_total 710
telemt_upstream_connect_attempt_total 10728
telemt_upstream_connect_success_total 10666
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 2809627
telemt_me_reconnect_success_total 318
telemt_me_reader_eof_total 250
telemt_me_idle_close_by_peer_total 250
telemt_me_route_drop_no_conn_total 13044
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33911
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 68
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_me_writer_removed_unexpected_total 272
telemt_me_refill_failed_total 99529
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_user_connections_total{user="hello"} 44222
telemt_user_connections_current{user="hello"} 2952
telemt_user_octets_from_client{user="hello"} 324568566 (309.53 MB)
telemt_user_octets_to_client{user="hello"} 8382385061 (7.81 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 805
telemt_user_unique_ips_recent_window{user="hello"} 375
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 420.5 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40431
telemt_connections_bad_total 998
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 9851
telemt_upstream_connect_success_total 9850
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982161
telemt_me_reconnect_success_total 282
telemt_me_reader_eof_total 182
telemt_me_idle_close_by_peer_total 182
telemt_me_route_drop_no_conn_total 6973
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24940
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_me_writer_removed_unexpected_total 204
telemt_me_refill_failed_total 107151
telemt_me_writer_restored_same_endpoint_total 167
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 34435
telemt_user_connections_current{user="hello"} 2640
telemt_user_octets_from_client{user="hello"} 393320077 (375.10 MB)
telemt_user_octets_to_client{user="hello"} 9709939381 (9.04 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 749
telemt_user_unique_ips_recent_window{user="hello"} 367
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 305.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7072
telemt_connections_bad_total 1583
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 112
telemt_upstream_connect_success_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_me_reconnect_attempts_total 43
telemt_me_reconnect_success_total 43
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 1419
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5174
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 29
telemt_me_writer_restored_same_endpoint_total 35
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 5174
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 265314576 (253.02 MB)
telemt_user_octets_to_client{user="hello"} 598541672 (570.81 MB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 376.4 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20965
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 493
telemt_upstream_connect_attempt_total 139
telemt_upstream_connect_success_total 128
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 62
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 8483
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18875
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_writer_removed_unexpected_total 40
telemt_me_writer_restored_same_endpoint_total 49
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 18845
telemt_user_connections_current{user="hello"} 1747
telemt_user_octets_from_client{user="hello"} 225132920 (214.70 MB)
telemt_user_octets_to_client{user="hello"} 6867578384 (6.40 GB)
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 267
```