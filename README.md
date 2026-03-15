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

# Server Metrics 2026-03-15 10:48:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 45230.7 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189469
telemt_connections_bad_total 1342
telemt_handshake_timeouts_total 4303
telemt_upstream_connect_attempt_total 11363
telemt_upstream_connect_success_total 11303
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6244
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 11400
telemt_me_reconnect_success_total 9027
telemt_me_reader_eof_total 9657
telemt_me_idle_close_by_peer_total 9657
telemt_me_route_drop_no_conn_total 413940
telemt_me_route_drop_channel_closed_total 62
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237636
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1428
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 864
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 568
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9184
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 8996
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 176893
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 2978879980 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 181463904400 (169.00 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 45237.1 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61472
telemt_connections_bad_total 2310
telemt_handshake_timeouts_total 3058
telemt_upstream_connect_attempt_total 12199
telemt_upstream_connect_success_total 12199
telemt_upstream_connect_attempts_per_request{bucket="1"} 12199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12226
telemt_me_reconnect_success_total 9903
telemt_me_reader_eof_total 10640
telemt_me_idle_close_by_peer_total 10640
telemt_me_route_drop_no_conn_total 28759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54130
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10083
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9887
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 54132
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 1032185388 (984.37 MB)
telemt_user_octets_to_client{user="hello"} 23126226680 (21.54 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 45229.6 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69059
telemt_connections_bad_total 691
telemt_handshake_timeouts_total 2441
telemt_upstream_connect_attempt_total 12642
telemt_upstream_connect_success_total 12641
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 11547
telemt_me_reconnect_success_total 10347
telemt_me_reader_eof_total 11136
telemt_me_idle_close_by_peer_total 11136
telemt_me_route_drop_no_conn_total 26066
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63223
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 36
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10476
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10343
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 63141
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 9346788788 (8.70 GB)
telemt_user_octets_to_client{user="hello"} 39036529952 (36.36 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 45229.3 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90071
telemt_connections_bad_total 276
telemt_handshake_timeouts_total 598
telemt_upstream_connect_attempt_total 10774
telemt_upstream_connect_success_total 10773
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8541
telemt_me_reconnect_success_total 8499
telemt_me_reader_eof_total 9076
telemt_me_idle_close_by_peer_total 9076
telemt_me_route_drop_no_conn_total 37126
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82197
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 180
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8587
telemt_me_writer_restored_same_endpoint_total 8488
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 82127
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1609782660 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 50086714552 (46.65 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 20300.7 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34471
telemt_connections_bad_total 3790
telemt_handshake_timeouts_total 496
telemt_upstream_connect_attempt_total 6779
telemt_upstream_connect_success_total 6726
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 6779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 99936
telemt_me_reconnect_success_total 5526
telemt_me_reader_eof_total 5736
telemt_me_idle_close_by_peer_total 5736
telemt_me_route_drop_no_conn_total 11843
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29348
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5500
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 5422
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 29488
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 440819433 (420.40 MB)
telemt_user_octets_to_client{user="hello"} 13039838591 (12.14 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 45228.5 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244654
telemt_connections_bad_total 44434
telemt_handshake_timeouts_total 1722
telemt_upstream_connect_attempt_total 9641
telemt_upstream_connect_success_total 9582
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 9641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 7340
telemt_me_reconnect_success_total 7297
telemt_me_reader_eof_total 7775
telemt_me_idle_close_by_peer_total 7775
telemt_me_route_drop_no_conn_total 107624
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191619
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 83
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7352
telemt_me_writer_restored_same_endpoint_total 7270
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 189988
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 4514578636 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 95819234324 (89.24 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 77
```