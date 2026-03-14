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

# Server Metrics 2026-03-14 07:23:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 172184.3 (47h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 660317
telemt_connections_bad_total 32379
telemt_handshake_timeouts_total 13064
telemt_upstream_connect_attempt_total 43884
telemt_upstream_connect_success_total 43662
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 43884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5684
telemt_me_reconnect_attempts_total 39383
telemt_me_reconnect_success_total 34691
telemt_me_reader_eof_total 37098
telemt_me_idle_close_by_peer_total 37097
telemt_me_route_drop_no_conn_total 218036
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 561929
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2107
telemt_desync_full_logged_total 721
telemt_desync_suppressed_total 1386
telemt_desync_frames_bucket_total{bucket="1_2"} 454
telemt_desync_frames_bucket_total{bucket="3_10"} 774
telemt_desync_frames_bucket_total{bucket="gt_10"} 879
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 35208
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34671
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 561812
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 16369348662 (15.25 GB)
telemt_user_octets_to_client{user="hello"} 270024744276 (251.48 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 172076.9 (47h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332629
telemt_connections_bad_total 2327
telemt_handshake_timeouts_total 2549
telemt_upstream_connect_attempt_total 150611
telemt_upstream_connect_success_total 149331
telemt_upstream_connect_fail_total 1280
telemt_upstream_connect_attempts_per_request{bucket="1"} 150611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1280
telemt_me_keepalive_timeout_total 4020
telemt_me_reconnect_attempts_total 178029
telemt_me_reconnect_success_total 37438
telemt_me_reader_eof_total 42832
telemt_me_idle_close_by_peer_total 42832
telemt_me_route_drop_no_conn_total 109866
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211816
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
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
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 42181
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 37421
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4743
telemt_user_connections_total{user="hello"} 314924
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 3274547123 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 102992014523 (95.92 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 172040.8 (47h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388767
telemt_connections_bad_total 3170
telemt_handshake_timeouts_total 35186
telemt_upstream_connect_attempt_total 45354
telemt_upstream_connect_success_total 45345
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3486
telemt_me_reconnect_attempts_total 38003
telemt_me_reconnect_success_total 36717
telemt_me_reader_eof_total 39478
telemt_me_idle_close_by_peer_total 39478
telemt_me_route_drop_no_conn_total 140234
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336870
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
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
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 37161
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36696
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 444
telemt_user_connections_total{user="hello"} 336642
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 13530550912 (12.60 GB)
telemt_user_octets_to_client{user="hello"} 134318579640 (125.09 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 172016.2 (47h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490756
telemt_connections_bad_total 16261
telemt_handshake_timeouts_total 4532
telemt_upstream_connect_attempt_total 75760
telemt_upstream_connect_success_total 65174
telemt_upstream_connect_fail_total 10586
telemt_upstream_connect_attempts_per_request{bucket="1"} 75760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10586
telemt_me_keepalive_timeout_total 5407
telemt_me_reconnect_attempts_total 143629
telemt_me_reconnect_success_total 37568
telemt_me_reader_eof_total 42100
telemt_me_idle_close_by_peer_total 42092
telemt_me_route_drop_no_conn_total 177530
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417864
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1783
telemt_desync_full_logged_total 533
telemt_desync_suppressed_total 1250
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 680
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 41309
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37558
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3741
telemt_user_connections_total{user="hello"} 436742
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 9426979423 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 179346486836 (167.03 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 122187.7 (33h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199086
telemt_connections_bad_total 29440
telemt_handshake_timeouts_total 1737
telemt_upstream_connect_attempt_total 43044
telemt_upstream_connect_success_total 42634
telemt_upstream_connect_fail_total 410
telemt_upstream_connect_attempts_per_request{bucket="1"} 43044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 410
telemt_me_keepalive_timeout_total 2528
telemt_me_reconnect_attempts_total 45109
telemt_me_reconnect_success_total 31677
telemt_me_reader_eof_total 33915
telemt_me_idle_close_by_peer_total 33915
telemt_me_route_drop_no_conn_total 59307
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157589
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 681
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 32388
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31659
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 162338
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 2407317705 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 75224858291 (70.06 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 171972.2 (47h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 984956
telemt_connections_bad_total 36087
telemt_handshake_timeouts_total 26145
telemt_upstream_connect_attempt_total 35659
telemt_upstream_connect_success_total 35470
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 35659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 4720
telemt_me_reconnect_attempts_total 31636
telemt_me_reconnect_success_total 26956
telemt_me_reader_eof_total 28937
telemt_me_idle_close_by_peer_total 28934
telemt_me_route_drop_no_conn_total 463714
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 912651
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 27446
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26949
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 885296
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 15169272532 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 446333233616 (415.68 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 51
```