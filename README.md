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

# Server Metrics 2026-03-15 09:21:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 40024.5 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153618
telemt_connections_bad_total 1151
telemt_handshake_timeouts_total 3870
telemt_upstream_connect_attempt_total 9903
telemt_upstream_connect_success_total 9847
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 9903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 9063
telemt_me_reconnect_success_total 7849
telemt_me_reader_eof_total 8404
telemt_me_idle_close_by_peer_total 8404
telemt_me_route_drop_no_conn_total 324222
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193796
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1145
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 458
telemt_desync_frames_bucket_total{bucket="gt_10"} 495
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7958
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 7818
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 142941
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 2013205856 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 147504860456 (137.37 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 40031.5 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47999
telemt_connections_bad_total 300
telemt_handshake_timeouts_total 2820
telemt_upstream_connect_attempt_total 10841
telemt_upstream_connect_success_total 10841
telemt_upstream_connect_attempts_per_request{bucket="1"} 10841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11133
telemt_me_reconnect_success_total 8816
telemt_me_reader_eof_total 9488
telemt_me_idle_close_by_peer_total 9488
telemt_me_route_drop_no_conn_total 23882
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43245
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8978
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 8800
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 43246
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 914642632 (872.27 MB)
telemt_user_octets_to_client{user="hello"} 16064621056 (14.96 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 40024.3 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56931
telemt_connections_bad_total 498
telemt_handshake_timeouts_total 1948
telemt_upstream_connect_attempt_total 10659
telemt_upstream_connect_success_total 10658
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8688
telemt_me_reconnect_success_total 8643
telemt_me_reader_eof_total 9330
telemt_me_idle_close_by_peer_total 9330
telemt_me_route_drop_no_conn_total 20785
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52113
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8727
telemt_me_writer_restored_same_endpoint_total 8639
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 52042
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 9209973324 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 33769747036 (31.45 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 40024.0 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71774
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 435
telemt_upstream_connect_attempt_total 9540
telemt_upstream_connect_success_total 9539
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7574
telemt_me_reconnect_success_total 7542
telemt_me_reader_eof_total 8062
telemt_me_idle_close_by_peer_total 8062
telemt_me_route_drop_no_conn_total 30579
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65217
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 95
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7620
telemt_me_writer_restored_same_endpoint_total 7531
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 65149
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 1291616600 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 40319920540 (37.55 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 15095.3 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24497
telemt_connections_bad_total 2858
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 5203
telemt_upstream_connect_success_total 5156
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 5203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_reconnect_attempts_total 98631
telemt_me_reconnect_success_total 4226
telemt_me_reader_eof_total 4364
telemt_me_idle_close_by_peer_total 4364
telemt_me_route_drop_no_conn_total 7801
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20637
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4187
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 4122
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 20777
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 183837725 (175.32 MB)
telemt_user_octets_to_client{user="hello"} 10906917351 (10.16 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 40023.3 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183022
telemt_connections_bad_total 22744
telemt_handshake_timeouts_total 1113
telemt_upstream_connect_attempt_total 8603
telemt_upstream_connect_success_total 8553
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 8603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 6582
telemt_me_reconnect_success_total 6548
telemt_me_reader_eof_total 6987
telemt_me_idle_close_by_peer_total 6987
telemt_me_route_drop_no_conn_total 87081
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154258
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6588
telemt_me_writer_restored_same_endpoint_total 6521
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 152798
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 4095871092 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 78261039956 (72.89 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 67
```