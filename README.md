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

# Server Metrics 2026-03-13 00:08:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 59691.1 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254757
telemt_connections_bad_total 2753
telemt_handshake_timeouts_total 5275
telemt_upstream_connect_attempt_total 15020
telemt_upstream_connect_success_total 14954
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 15020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1493
telemt_me_reconnect_attempts_total 15397
telemt_me_reconnect_success_total 11926
telemt_me_reader_eof_total 12717
telemt_me_idle_close_by_peer_total 12716
telemt_me_route_drop_no_conn_total 79230
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210795
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 711
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12169
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 11910
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 210563
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 3882149344 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 107875927584 (100.47 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 59584.1 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116999
telemt_connections_bad_total 651
telemt_handshake_timeouts_total 928
telemt_upstream_connect_attempt_total 33932
telemt_upstream_connect_success_total 33537
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 33932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 420
telemt_me_reconnect_attempts_total 55894
telemt_me_reconnect_success_total 14022
telemt_me_reader_eof_total 15706
telemt_me_idle_close_by_peer_total 15706
telemt_me_route_drop_no_conn_total 42239
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94557
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 15431
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 14007
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1409
telemt_user_connections_total{user="hello"} 111059
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 1215076132 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 34244327863 (31.89 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 59547.9 (16h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142699
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 2247
telemt_upstream_connect_attempt_total 16369
telemt_upstream_connect_success_total 16367
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 347
telemt_me_reconnect_attempts_total 14463
telemt_me_reconnect_success_total 13312
telemt_me_reader_eof_total 14221
telemt_me_idle_close_by_peer_total 14221
telemt_me_route_drop_no_conn_total 53961
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133450
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13480
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 13292
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 133416
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 2618180788 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 62133246924 (57.87 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 59523.4 (16h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205752
telemt_connections_bad_total 13281
telemt_handshake_timeouts_total 1382
telemt_upstream_connect_attempt_total 28198
telemt_upstream_connect_success_total 18467
telemt_upstream_connect_fail_total 9731
telemt_upstream_connect_attempts_per_request{bucket="1"} 28198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9731
telemt_me_keepalive_timeout_total 3186
telemt_me_reconnect_attempts_total 44842
telemt_me_reconnect_success_total 12588
telemt_me_reader_eof_total 14049
telemt_me_idle_close_by_peer_total 14042
telemt_me_route_drop_no_conn_total 73288
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169690
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13788
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 12578
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1200
telemt_user_connections_total{user="hello"} 172444
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 2997880906 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 70528825157 (65.69 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9694.9 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8544
telemt_connections_bad_total 1795
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 3070
telemt_upstream_connect_success_total 3041
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 3070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2543
telemt_me_reconnect_success_total 2538
telemt_me_reader_eof_total 2695
telemt_me_idle_close_by_peer_total 2695
telemt_me_route_drop_no_conn_total 2610
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6453
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2551
telemt_me_writer_restored_same_endpoint_total 2522
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 6453
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 22853732 (21.80 MB)
telemt_user_octets_to_client{user="hello"} 2228897456 (2.08 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 59479.9 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340463
telemt_connections_bad_total 5283
telemt_handshake_timeouts_total 2552
telemt_upstream_connect_attempt_total 12540
telemt_upstream_connect_success_total 12470
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1291
telemt_me_reconnect_attempts_total 13098
telemt_me_reconnect_success_total 9482
telemt_me_reader_eof_total 10168
telemt_me_idle_close_by_peer_total 10166
telemt_me_route_drop_no_conn_total 152325
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334475
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9711
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9475
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 322775
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 5544071544 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 173369738624 (161.46 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 28
```