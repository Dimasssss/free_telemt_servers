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

# Server Metrics 2026-03-14 01:11:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 149879.4 (41h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 594584
telemt_connections_bad_total 21478
telemt_handshake_timeouts_total 12856
telemt_upstream_connect_attempt_total 38140
telemt_upstream_connect_success_total 37952
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 38140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5479
telemt_me_reconnect_attempts_total 34755
telemt_me_reconnect_success_total 30082
telemt_me_reader_eof_total 32145
telemt_me_idle_close_by_peer_total 32144
telemt_me_route_drop_no_conn_total 195300
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509297
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1645
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 1081
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 617
telemt_desync_frames_bucket_total{bucket="gt_10"} 674
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 30558
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 30066
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 509192
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 15489352058 (14.43 GB)
telemt_user_octets_to_client{user="hello"} 251295251564 (234.04 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 149772.1 (41h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304927
telemt_connections_bad_total 2235
telemt_handshake_timeouts_total 1934
telemt_upstream_connect_attempt_total 142783
telemt_upstream_connect_success_total 141679
telemt_upstream_connect_fail_total 1104
telemt_upstream_connect_attempts_per_request{bucket="1"} 142783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1104
telemt_me_keepalive_timeout_total 3788
telemt_me_reconnect_attempts_total 161828
telemt_me_reconnect_success_total 30883
telemt_me_reader_eof_total 35767
telemt_me_idle_close_by_peer_total 35767
telemt_me_route_drop_no_conn_total 94898
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185971
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 35262
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 30866
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4379
telemt_user_connections_total{user="hello"} 289083
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 3027625395 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 90313467955 (84.11 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 149735.6 (41h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357045
telemt_connections_bad_total 2821
telemt_handshake_timeouts_total 33211
telemt_upstream_connect_attempt_total 39743
telemt_upstream_connect_success_total 39737
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 39743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3256
telemt_me_reconnect_attempts_total 33480
telemt_me_reconnect_success_total 32217
telemt_me_reader_eof_total 34614
telemt_me_idle_close_by_peer_total 34614
telemt_me_route_drop_no_conn_total 126642
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308546
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 32598
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 32197
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 308446
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 12590218928 (11.73 GB)
telemt_user_octets_to_client{user="hello"} 126711448296 (118.01 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 149711.4 (41h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458354
telemt_connections_bad_total 15366
telemt_handshake_timeouts_total 4320
telemt_upstream_connect_attempt_total 67967
telemt_upstream_connect_success_total 57522
telemt_upstream_connect_fail_total 10444
telemt_upstream_connect_attempts_per_request{bucket="1"} 67966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10444
telemt_me_keepalive_timeout_total 5059
telemt_me_reconnect_attempts_total 135993
telemt_me_reconnect_success_total 31015
telemt_me_reader_eof_total 35200
telemt_me_idle_close_by_peer_total 35192
telemt_me_route_drop_no_conn_total 161684
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388327
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1698
telemt_desync_full_logged_total 499
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 398
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 34670
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 31005
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3655
telemt_user_connections_total{user="hello"} 407169
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 9057651611 (8.44 GB)
telemt_user_octets_to_client{user="hello"} 155322271144 (144.66 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 99883.0 (27h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166976
telemt_connections_bad_total 24395
telemt_handshake_timeouts_total 1553
telemt_upstream_connect_attempt_total 36697
telemt_upstream_connect_success_total 36364
telemt_upstream_connect_fail_total 333
telemt_upstream_connect_attempts_per_request{bucket="1"} 36697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 333
telemt_me_keepalive_timeout_total 1366
telemt_me_reconnect_attempts_total 39917
telemt_me_reconnect_success_total 26505
telemt_me_reader_eof_total 28341
telemt_me_idle_close_by_peer_total 28341
telemt_me_route_drop_no_conn_total 49844
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131268
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 27165
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 26487
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 136086
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 1818163217 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 64175507767 (59.77 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 149667.4 (41h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 876199
telemt_connections_bad_total 27445
telemt_handshake_timeouts_total 25319
telemt_upstream_connect_attempt_total 30853
telemt_upstream_connect_success_total 30687
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 30853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 3413
telemt_me_reconnect_attempts_total 27923
telemt_me_reconnect_success_total 23258
telemt_me_reader_eof_total 24930
telemt_me_idle_close_by_peer_total 24927
telemt_me_route_drop_no_conn_total 417224
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 818683
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 23706
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23251
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 791439
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 14110386880 (13.14 GB)
telemt_user_octets_to_client{user="hello"} 404742394904 (376.95 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 41
```