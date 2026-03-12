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

# Server Metrics 2026-03-12 21:24:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 49851.8 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236962
telemt_connections_bad_total 2675
telemt_handshake_timeouts_total 5170
telemt_upstream_connect_attempt_total 12505
telemt_upstream_connect_success_total 12448
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 12505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1461
telemt_me_reconnect_attempts_total 13365
telemt_me_reconnect_success_total 9899
telemt_me_reader_eof_total 10527
telemt_me_idle_close_by_peer_total 10526
telemt_me_route_drop_no_conn_total 72759
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195848
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 10121
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 9883
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 195615
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 3691937084 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 94778543532 (88.27 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 49744.5 (13h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105755
telemt_connections_bad_total 547
telemt_handshake_timeouts_total 804
telemt_upstream_connect_attempt_total 30341
telemt_upstream_connect_success_total 30020
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 30341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 496
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 371
telemt_me_reconnect_attempts_total 51636
telemt_me_reconnect_success_total 10987
telemt_me_reader_eof_total 12494
telemt_me_idle_close_by_peer_total 12494
telemt_me_route_drop_no_conn_total 38328
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84064
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 12338
telemt_me_refill_failed_total 1269
telemt_me_writer_restored_same_endpoint_total 10972
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1351
telemt_user_connections_total{user="hello"} 100567
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 1096558600 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 29974736635 (27.92 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 49708.1 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131804
telemt_connections_bad_total 1553
telemt_handshake_timeouts_total 2208
telemt_upstream_connect_attempt_total 13745
telemt_upstream_connect_success_total 13744
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 303
telemt_me_reconnect_attempts_total 12313
telemt_me_reconnect_success_total 11173
telemt_me_reader_eof_total 11902
telemt_me_idle_close_by_peer_total 11902
telemt_me_route_drop_no_conn_total 49827
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122982
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 47
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 11316
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 11153
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 122948
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 2547963392 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 59571562408 (55.48 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 49683.7 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191965
telemt_connections_bad_total 13177
telemt_handshake_timeouts_total 1289
telemt_upstream_connect_attempt_total 24758
telemt_upstream_connect_success_total 15087
telemt_upstream_connect_fail_total 9671
telemt_upstream_connect_attempts_per_request{bucket="1"} 24758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9671
telemt_me_keepalive_timeout_total 2457
telemt_me_reconnect_attempts_total 41931
telemt_me_reconnect_success_total 9689
telemt_me_reader_eof_total 11018
telemt_me_idle_close_by_peer_total 11011
telemt_me_route_drop_no_conn_total 66833
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156328
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 10855
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 9679
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1166
telemt_user_connections_total{user="hello"} 159083
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2920471498 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 62464569793 (58.17 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 49640.2 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308685
telemt_connections_bad_total 4089
telemt_handshake_timeouts_total 2451
telemt_upstream_connect_attempt_total 10381
telemt_upstream_connect_success_total 10325
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 10381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 492
telemt_me_reconnect_attempts_total 11416
telemt_me_reconnect_success_total 7808
telemt_me_reader_eof_total 8340
telemt_me_idle_close_by_peer_total 8339
telemt_me_route_drop_no_conn_total 141053
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304569
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 285
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8017
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7801
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 292874
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 5251401372 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 143147051700 (133.32 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 34
```