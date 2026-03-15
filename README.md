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

# Server Metrics 2026-03-15 08:20:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 36361.7 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130916
telemt_connections_bad_total 1053
telemt_handshake_timeouts_total 3351
telemt_upstream_connect_attempt_total 8741
telemt_upstream_connect_success_total 8688
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 8741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4784
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6897
telemt_me_reconnect_success_total 6871
telemt_me_reader_eof_total 7358
telemt_me_idle_close_by_peer_total 7358
telemt_me_route_drop_no_conn_total 258571
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158700
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 964
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 554
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 394
telemt_desync_frames_bucket_total{bucket="gt_10"} 407
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6933
telemt_me_writer_restored_same_endpoint_total 6840
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 121636
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 1663330492 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 111516539216 (103.86 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 36368.1 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39407
telemt_connections_bad_total 257
telemt_handshake_timeouts_total 1622
telemt_upstream_connect_attempt_total 9821
telemt_upstream_connect_success_total 9821
telemt_upstream_connect_attempts_per_request{bucket="1"} 9821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8020
telemt_me_reconnect_success_total 7986
telemt_me_reader_eof_total 8556
telemt_me_idle_close_by_peer_total 8556
telemt_me_route_drop_no_conn_total 20477
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36130
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8066
telemt_me_writer_restored_same_endpoint_total 7970
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 36133
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 844272620 (805.16 MB)
telemt_user_octets_to_client{user="hello"} 13449939484 (12.53 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 36360.7 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49640
telemt_connections_bad_total 479
telemt_handshake_timeouts_total 1904
telemt_upstream_connect_attempt_total 9711
telemt_upstream_connect_success_total 9710
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7915
telemt_me_reconnect_success_total 7878
telemt_me_reader_eof_total 8518
telemt_me_idle_close_by_peer_total 8518
telemt_me_route_drop_no_conn_total 16930
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45110
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7952
telemt_me_writer_restored_same_endpoint_total 7874
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 45046
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 8921347680 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 27292021112 (25.42 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 36360.3 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59179
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 395
telemt_upstream_connect_attempt_total 8696
telemt_upstream_connect_success_total 8695
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6904
telemt_me_reconnect_success_total 6876
telemt_me_reader_eof_total 7353
telemt_me_idle_close_by_peer_total 7353
telemt_me_route_drop_no_conn_total 25734
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53535
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 105
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6947
telemt_me_writer_restored_same_endpoint_total 6865
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 53468
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 1083943488 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 33272239144 (30.99 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 11431.9 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17870
telemt_connections_bad_total 2193
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 4085
telemt_upstream_connect_success_total 4046
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 4085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 97698
telemt_me_reconnect_success_total 3298
telemt_me_reader_eof_total 3386
telemt_me_idle_close_by_peer_total 3386
telemt_me_route_drop_no_conn_total 5284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14983
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3249
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3194
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 15123
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 121717825 (116.08 MB)
telemt_user_octets_to_client{user="hello"} 9696338607 (9.03 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 36359.9 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156880
telemt_connections_bad_total 20455
telemt_handshake_timeouts_total 804
telemt_upstream_connect_attempt_total 7926
telemt_upstream_connect_success_total 7878
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 7926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 6080
telemt_me_reconnect_success_total 6050
telemt_me_reader_eof_total 6450
telemt_me_idle_close_by_peer_total 6450
telemt_me_route_drop_no_conn_total 74788
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131401
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6083
telemt_me_writer_restored_same_endpoint_total 6023
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 129939
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 3553668580 (3.31 GB)
telemt_user_octets_to_client{user="hello"} 70067578860 (65.26 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 61
```