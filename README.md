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

# Server Metrics 2026-03-13 05:51:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 80259.9 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304319
telemt_connections_bad_total 3077
telemt_handshake_timeouts_total 6232
telemt_upstream_connect_attempt_total 20186
telemt_upstream_connect_success_total 20089
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 20186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1579
telemt_me_reconnect_attempts_total 19537
telemt_me_reconnect_success_total 16039
telemt_me_reader_eof_total 17148
telemt_me_idle_close_by_peer_total 17147
telemt_me_route_drop_no_conn_total 94942
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256688
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 884
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 556
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 385
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16321
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16023
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 256624
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 4370456876 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 124049233324 (115.53 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 80152.7 (22h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138907
telemt_connections_bad_total 762
telemt_handshake_timeouts_total 1041
telemt_upstream_connect_attempt_total 42396
telemt_upstream_connect_success_total 41859
telemt_upstream_connect_fail_total 537
telemt_upstream_connect_attempts_per_request{bucket="1"} 42396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 537
telemt_me_keepalive_timeout_total 593
telemt_me_reconnect_attempts_total 67923
telemt_me_reconnect_success_total 21358
telemt_me_reader_eof_total 23463
telemt_me_idle_close_by_peer_total 23463
telemt_me_route_drop_no_conn_total 51928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115505
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 22978
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 21343
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1620
telemt_user_connections_total{user="hello"} 132003
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 1377128552 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 39958811347 (37.21 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 80117.6 (22h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168356
telemt_connections_bad_total 1896
telemt_handshake_timeouts_total 2718
telemt_upstream_connect_attempt_total 22029
telemt_upstream_connect_success_total 22027
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11874
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 465
telemt_me_reconnect_attempts_total 19169
telemt_me_reconnect_success_total 18001
telemt_me_reader_eof_total 19288
telemt_me_idle_close_by_peer_total 19288
telemt_me_route_drop_no_conn_total 65294
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157455
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 18197
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17981
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 157383
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 2925915112 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 71816302752 (66.88 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 80092.2 (22h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243052
telemt_connections_bad_total 13565
telemt_handshake_timeouts_total 1813
telemt_upstream_connect_attempt_total 34187
telemt_upstream_connect_success_total 24283
telemt_upstream_connect_fail_total 9904
telemt_upstream_connect_attempts_per_request{bucket="1"} 34187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9904
telemt_me_keepalive_timeout_total 3317
telemt_me_reconnect_attempts_total 68971
telemt_me_reconnect_success_total 17439
telemt_me_reader_eof_total 19581
telemt_me_idle_close_by_peer_total 19574
telemt_me_route_drop_no_conn_total 88803
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204048
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 579
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 411
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 19274
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17429
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1835
telemt_user_connections_total{user="hello"} 206790
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 3309967122 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 81632799165 (76.03 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 30263.6 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32476
telemt_connections_bad_total 5679
telemt_handshake_timeouts_total 137
telemt_upstream_connect_attempt_total 10193
telemt_upstream_connect_success_total 10092
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 10193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 245
telemt_me_reconnect_attempts_total 9531
telemt_me_reconnect_success_total 8571
telemt_me_reader_eof_total 9139
telemt_me_idle_close_by_peer_total 9139
telemt_me_route_drop_no_conn_total 9203
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25794
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 8680
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 8553
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 25794
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 202919748 (193.52 MB)
telemt_user_octets_to_client{user="hello"} 9537581196 (8.88 GB)
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 80048.5 (22h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410434
telemt_connections_bad_total 7988
telemt_handshake_timeouts_total 3088
telemt_upstream_connect_attempt_total 17036
telemt_upstream_connect_success_total 16942
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 17036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1451
telemt_me_reconnect_attempts_total 16609
telemt_me_reconnect_success_total 12977
telemt_me_reader_eof_total 13933
telemt_me_idle_close_by_peer_total 13930
telemt_me_route_drop_no_conn_total 182291
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398303
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 343
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 13254
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12970
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 386548
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 6365236908 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 228001344268 (212.34 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 42
```