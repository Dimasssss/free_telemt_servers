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

# Server Metrics 2026-03-13 18:18:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 125127.3 (34h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528747
telemt_connections_bad_total 9771
telemt_handshake_timeouts_total 12164
telemt_upstream_connect_attempt_total 31414
telemt_upstream_connect_success_total 31259
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 31414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3462
telemt_me_reconnect_attempts_total 29653
telemt_me_reconnect_success_total 25011
telemt_me_reader_eof_total 26704
telemt_me_idle_close_by_peer_total 26703
telemt_me_route_drop_no_conn_total 172679
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 458702
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1469
telemt_desync_full_logged_total 509
telemt_desync_suppressed_total 960
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 25433
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 24995
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 422
telemt_user_connections_total{user="hello"} 458272
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 8435576380 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 217391024004 (202.46 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 125020.3 (34h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261300
telemt_connections_bad_total 1953
telemt_handshake_timeouts_total 1837
telemt_upstream_connect_attempt_total 114335
telemt_upstream_connect_success_total 113483
telemt_upstream_connect_fail_total 852
telemt_upstream_connect_attempts_per_request{bucket="1"} 114335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1675
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 852
telemt_me_keepalive_timeout_total 1519
telemt_me_reconnect_attempts_total 128704
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29995
telemt_me_idle_close_by_peer_total 29995
telemt_me_route_drop_no_conn_total 82959
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166482
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 31
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29465
telemt_me_refill_failed_total 3204
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3432
telemt_user_connections_total{user="hello"} 247493
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 2575451834 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 76095261423 (70.87 GB)
telemt_user_msgs_from_client{user="hello"} 1276801
telemt_user_msgs_to_client{user="hello"} 7407945
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 124984.0 (34h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309291
telemt_connections_bad_total 2615
telemt_handshake_timeouts_total 19084
telemt_upstream_connect_attempt_total 33287
telemt_upstream_connect_success_total 33283
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 33287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2689
telemt_me_reconnect_attempts_total 28240
telemt_me_reconnect_success_total 27010
telemt_me_reader_eof_total 28964
telemt_me_idle_close_by_peer_total 28964
telemt_me_route_drop_no_conn_total 110347
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276733
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 27313
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26990
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 276646
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 10302093936 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 113471612528 (105.68 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 124959.3 (34h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414717
telemt_connections_bad_total 15129
telemt_handshake_timeouts_total 3887
telemt_upstream_connect_attempt_total 60640
telemt_upstream_connect_success_total 50385
telemt_upstream_connect_fail_total 10255
telemt_upstream_connect_attempts_per_request{bucket="1"} 60640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10255
telemt_me_keepalive_timeout_total 4676
telemt_me_reconnect_attempts_total 114780
telemt_me_reconnect_success_total 25123
telemt_me_reader_eof_total 28652
telemt_me_idle_close_by_peer_total 28645
telemt_me_route_drop_no_conn_total 142999
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346669
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1355
telemt_desync_full_logged_total 404
telemt_desync_suppressed_total 951
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 500
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 28243
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 25113
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3120
telemt_user_connections_total{user="hello"} 365559
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 8392223843 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 130255115636 (121.31 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 75130.8 (20h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124411
telemt_connections_bad_total 15563
telemt_handshake_timeouts_total 1404
telemt_upstream_connect_attempt_total 29460
telemt_upstream_connect_success_total 29184
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 29460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_keepalive_timeout_total 1189
telemt_me_reconnect_attempts_total 33907
telemt_me_reconnect_success_total 20519
telemt_me_reader_eof_total 21998
telemt_me_idle_close_by_peer_total 21998
telemt_me_route_drop_no_conn_total 38989
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98550
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 488
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 21127
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20501
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 608
telemt_user_connections_total{user="hello"} 103447
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 1214437273 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 34505023911 (32.14 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 124916.0 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 763919
telemt_connections_bad_total 24763
telemt_handshake_timeouts_total 24535
telemt_upstream_connect_attempt_total 25931
telemt_upstream_connect_success_total 25793
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 25931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 2992
telemt_me_reconnect_attempts_total 24243
telemt_me_reconnect_success_total 19600
telemt_me_reader_eof_total 21034
telemt_me_idle_close_by_peer_total 21031
telemt_me_route_drop_no_conn_total 362667
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716797
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 20003
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19593
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 403
telemt_user_connections_total{user="hello"} 689684
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 12068898140 (11.24 GB)
telemt_user_octets_to_client{user="hello"} 342574403392 (319.05 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 63
```