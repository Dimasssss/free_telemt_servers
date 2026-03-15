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

# Server Metrics 2026-03-15 06:03:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 28122.9 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73289
telemt_connections_bad_total 430
telemt_handshake_timeouts_total 1436
telemt_upstream_connect_attempt_total 6988
telemt_upstream_connect_success_total 6946
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 6988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5543
telemt_me_reconnect_success_total 5523
telemt_me_reader_eof_total 5916
telemt_me_idle_close_by_peer_total 5916
telemt_me_route_drop_no_conn_total 30601
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70137
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 576
telemt_desync_full_logged_total 260
telemt_desync_suppressed_total 316
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5564
telemt_me_writer_restored_same_endpoint_total 5492
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 68721
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 874310496 (833.81 MB)
telemt_user_octets_to_client{user="hello"} 27282425844 (25.41 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 28130.3 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25625
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 7670
telemt_upstream_connect_success_total 7670
telemt_upstream_connect_attempts_per_request{bucket="1"} 7670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6262
telemt_me_reconnect_success_total 6235
telemt_me_reader_eof_total 6709
telemt_me_idle_close_by_peer_total 6709
telemt_me_route_drop_no_conn_total 12988
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24379
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6292
telemt_me_writer_restored_same_endpoint_total 6219
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 24382
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 707767216 (674.98 MB)
telemt_user_octets_to_client{user="hello"} 8874846432 (8.27 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 28122.8 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33500
telemt_connections_bad_total 430
telemt_handshake_timeouts_total 1762
telemt_upstream_connect_attempt_total 7522
telemt_upstream_connect_success_total 7521
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6118
telemt_me_reconnect_success_total 6091
telemt_me_reader_eof_total 6590
telemt_me_idle_close_by_peer_total 6590
telemt_me_route_drop_no_conn_total 11563
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30215
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6145
telemt_me_writer_restored_same_endpoint_total 6087
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 30164
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 8761376156 (8.16 GB)
telemt_user_octets_to_client{user="hello"} 17184726260 (16.00 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 28122.4 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34740
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 6678
telemt_upstream_connect_success_total 6677
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5279
telemt_me_reconnect_success_total 5260
telemt_me_reader_eof_total 5637
telemt_me_idle_close_by_peer_total 5637
telemt_me_route_drop_no_conn_total 15784
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32322
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5314
telemt_me_writer_restored_same_endpoint_total 5249
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 32241
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 601923116 (574.04 MB)
telemt_user_octets_to_client{user="hello"} 21089922268 (19.64 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 3194.0 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4476
telemt_connections_bad_total 626
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 1489
telemt_upstream_connect_success_total 1461
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 95506
telemt_me_reconnect_success_total 1118
telemt_me_reader_eof_total 1068
telemt_me_idle_close_by_peer_total 1068
telemt_me_route_drop_no_conn_total 1112
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3572
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1042
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 1014
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 3717
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 23624013 (22.53 MB)
telemt_user_octets_to_client{user="hello"} 1449806647 (1.35 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 28121.8 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91969
telemt_connections_bad_total 1739
telemt_handshake_timeouts_total 399
telemt_upstream_connect_attempt_total 6241
telemt_upstream_connect_success_total 6205
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 6241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 4800
telemt_me_reconnect_success_total 4778
telemt_me_reader_eof_total 5088
telemt_me_idle_close_by_peer_total 5088
telemt_me_route_drop_no_conn_total 49270
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87372
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4797
telemt_me_writer_restored_same_endpoint_total 4751
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 85933
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 2166166120 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 47491183148 (44.23 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 46
```