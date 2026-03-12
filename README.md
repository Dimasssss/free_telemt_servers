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

# Server Metrics 2026-03-12 19:52:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 44339.0 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219795
telemt_connections_bad_total 2617
telemt_handshake_timeouts_total 5000
telemt_upstream_connect_attempt_total 11207
telemt_upstream_connect_success_total 11156
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 11207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1435
telemt_me_reconnect_attempts_total 12331
telemt_me_reconnect_success_total 8871
telemt_me_reader_eof_total 9415
telemt_me_idle_close_by_peer_total 9414
telemt_me_route_drop_no_conn_total 66733
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183547
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 642
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 401
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9083
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8855
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 183505
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 3366672124 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 85467783112 (79.60 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 44232.6 (12h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98872
telemt_connections_bad_total 516
telemt_handshake_timeouts_total 777
telemt_upstream_connect_attempt_total 28231
telemt_upstream_connect_success_total 27941
telemt_upstream_connect_fail_total 290
telemt_upstream_connect_attempts_per_request{bucket="1"} 28231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 483
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 290
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 48600
telemt_me_reconnect_success_total 9168
telemt_me_reader_eof_total 10572
telemt_me_idle_close_by_peer_total 10572
telemt_me_route_drop_no_conn_total 35795
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77420
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 12
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
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 10472
telemt_me_refill_failed_total 1231
telemt_me_writer_restored_same_endpoint_total 9153
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1304
telemt_user_connections_total{user="hello"} 93923
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 1031051484 (983.29 MB)
telemt_user_octets_to_client{user="hello"} 27780107455 (25.87 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 44196.2 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124446
telemt_connections_bad_total 1523
telemt_handshake_timeouts_total 2182
telemt_upstream_connect_attempt_total 12287
telemt_upstream_connect_success_total 12286
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 283
telemt_me_reconnect_attempts_total 11117
telemt_me_reconnect_success_total 9981
telemt_me_reader_eof_total 10602
telemt_me_idle_close_by_peer_total 10602
telemt_me_route_drop_no_conn_total 46727
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115855
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 10116
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 9961
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 115827
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 2487139060 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 56327425900 (52.46 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 44171.9 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179601
telemt_connections_bad_total 13151
telemt_handshake_timeouts_total 1272
telemt_upstream_connect_attempt_total 23064
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 9623
telemt_upstream_connect_attempts_per_request{bucket="1"} 23064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9623
telemt_me_keepalive_timeout_total 2427
telemt_me_reconnect_attempts_total 39503
telemt_me_reconnect_success_total 8321
telemt_me_reader_eof_total 9543
telemt_me_idle_close_by_peer_total 9536
telemt_me_route_drop_no_conn_total 61737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144323
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 9438
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 8311
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1117
telemt_user_connections_total{user="hello"} 147079
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 2674674306 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 58399454529 (54.39 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 44128.4 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279186
telemt_connections_bad_total 2148
telemt_handshake_timeouts_total 2192
telemt_upstream_connect_attempt_total 9243
telemt_upstream_connect_success_total 9197
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 9243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 483
telemt_me_reconnect_attempts_total 10585
telemt_me_reconnect_success_total 6979
telemt_me_reader_eof_total 7439
telemt_me_idle_close_by_peer_total 7438
telemt_me_route_drop_no_conn_total 130404
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277955
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 258
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7180
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6972
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 266264
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 4947869096 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 133860784452 (124.67 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 46
```