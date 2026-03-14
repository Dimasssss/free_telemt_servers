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

# Server Metrics 2026-03-14 20:28:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 25915.7 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133291
telemt_connections_bad_total 16088
telemt_handshake_timeouts_total 1344
telemt_upstream_connect_attempt_total 5835
telemt_upstream_connect_success_total 5833
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 4544
telemt_me_reconnect_success_total 4508
telemt_me_reader_eof_total 4779
telemt_me_idle_close_by_peer_total 4779
telemt_me_route_drop_no_conn_total 47961
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109968
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 478
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 306
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4586
telemt_me_writer_restored_same_endpoint_total 4490
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 109889
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 2364571020 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 63713643200 (59.34 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 25914.7 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54280
telemt_connections_bad_total 684
telemt_handshake_timeouts_total 962
telemt_upstream_connect_attempt_total 6679
telemt_upstream_connect_success_total 6637
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 6679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 7889
telemt_me_reconnect_success_total 5312
telemt_me_reader_eof_total 5653
telemt_me_idle_close_by_peer_total 5653
telemt_me_route_drop_no_conn_total 28357
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50519
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5465
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5307
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 50507
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 1313423240 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 21673291184 (20.18 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 25918.8 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60852
telemt_connections_bad_total 389
telemt_handshake_timeouts_total 1888
telemt_upstream_connect_attempt_total 8615
telemt_upstream_connect_success_total 8526
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 8615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 104746
telemt_me_reconnect_success_total 6883
telemt_me_reader_eof_total 7346
telemt_me_idle_close_by_peer_total 7346
telemt_me_route_drop_no_conn_total 23220
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55388
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 7159
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6837
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 55453
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 3815851657 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 40484724302 (37.70 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 25923.7 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78126
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 587
telemt_upstream_connect_attempt_total 6376
telemt_upstream_connect_success_total 6338
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 6376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 4874
telemt_me_reconnect_success_total 4849
telemt_me_reader_eof_total 5097
telemt_me_idle_close_by_peer_total 5097
telemt_me_route_drop_no_conn_total 33806
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73944
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 593
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 442
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4904
telemt_me_writer_restored_same_endpoint_total 4847
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 73992
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 1167603700 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 24814430542 (23.11 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 25916.8 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56877
telemt_connections_bad_total 4995
telemt_handshake_timeouts_total 3306
telemt_upstream_connect_attempt_total 6138
telemt_upstream_connect_success_total 6068
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 6138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 11273
telemt_me_reconnect_success_total 4738
telemt_me_reader_eof_total 5143
telemt_me_idle_close_by_peer_total 5143
telemt_me_route_drop_no_conn_total 18850
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45887
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4987
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4734
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 45874
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 1367712828 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 27233550488 (25.36 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 25916.4 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196990
telemt_connections_bad_total 7293
telemt_handshake_timeouts_total 2647
telemt_upstream_connect_attempt_total 5056
telemt_upstream_connect_success_total 4964
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 5056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 8646
telemt_me_reconnect_success_total 3640
telemt_me_reader_eof_total 3950
telemt_me_idle_close_by_peer_total 3950
telemt_me_route_drop_no_conn_total 110523
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181261
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3839
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3636
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 177750
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 3875596176 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 89410731676 (83.27 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 55
```