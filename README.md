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

# Server Metrics 2026-03-14 00:50:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 148657.2 (41h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592264
telemt_connections_bad_total 21161
telemt_handshake_timeouts_total 12851
telemt_upstream_connect_attempt_total 37853
telemt_upstream_connect_success_total 37665
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 37853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5178
telemt_me_reconnect_attempts_total 34512
telemt_me_reconnect_success_total 29840
telemt_me_reader_eof_total 31891
telemt_me_idle_close_by_peer_total 31890
telemt_me_route_drop_no_conn_total 194670
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507338
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1639
telemt_desync_full_logged_total 560
telemt_desync_suppressed_total 1079
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 614
telemt_desync_frames_bucket_total{bucket="gt_10"} 672
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 30316
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 29824
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 507233
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 15470374666 (14.41 GB)
telemt_user_octets_to_client{user="hello"} 250671422796 (233.46 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 148550.1 (41h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304199
telemt_connections_bad_total 2235
telemt_handshake_timeouts_total 1932
telemt_upstream_connect_attempt_total 142508
telemt_upstream_connect_success_total 141416
telemt_upstream_connect_fail_total 1092
telemt_upstream_connect_attempts_per_request{bucket="1"} 142508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1092
telemt_me_keepalive_timeout_total 3775
telemt_me_reconnect_attempts_total 158950
telemt_me_reconnect_success_total 30694
telemt_me_reader_eof_total 35492
telemt_me_idle_close_by_peer_total 35492
telemt_me_route_drop_no_conn_total 93946
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185285
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 38
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
telemt_me_writer_removed_unexpected_total 34987
telemt_me_refill_failed_total 4002
telemt_me_writer_restored_same_endpoint_total 30677
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4293
telemt_user_connections_total{user="hello"} 288397
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 3023989763 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 90229843847 (84.03 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 148513.7 (41h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355840
telemt_connections_bad_total 2774
telemt_handshake_timeouts_total 33209
telemt_upstream_connect_attempt_total 39364
telemt_upstream_connect_success_total 39358
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 39364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2966
telemt_me_reconnect_attempts_total 33188
telemt_me_reconnect_success_total 31927
telemt_me_reader_eof_total 34294
telemt_me_idle_close_by_peer_total 34294
telemt_me_route_drop_no_conn_total 126150
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307423
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
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 32304
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 31907
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 307324
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 12583301816 (11.72 GB)
telemt_user_octets_to_client{user="hello"} 126321456968 (117.65 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 148489.4 (41h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457271
telemt_connections_bad_total 15364
telemt_handshake_timeouts_total 4319
telemt_upstream_connect_attempt_total 67544
telemt_upstream_connect_success_total 57114
telemt_upstream_connect_fail_total 10430
telemt_upstream_connect_attempts_per_request{bucket="1"} 67544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10430
telemt_me_keepalive_timeout_total 5050
telemt_me_reconnect_attempts_total 135670
telemt_me_reconnect_success_total 30694
telemt_me_reader_eof_total 34862
telemt_me_idle_close_by_peer_total 34854
telemt_me_route_drop_no_conn_total 161094
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387274
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1692
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 34346
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 30684
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3652
telemt_user_connections_total{user="hello"} 406116
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 9051193915 (8.43 GB)
telemt_user_octets_to_client{user="hello"} 155166195816 (144.51 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 98660.9 (27h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165083
telemt_connections_bad_total 24167
telemt_handshake_timeouts_total 1551
telemt_upstream_connect_attempt_total 36310
telemt_upstream_connect_success_total 35981
telemt_upstream_connect_fail_total 329
telemt_upstream_connect_attempts_per_request{bucket="1"} 36310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 329
telemt_me_keepalive_timeout_total 1358
telemt_me_reconnect_attempts_total 39577
telemt_me_reconnect_success_total 26165
telemt_me_reader_eof_total 27969
telemt_me_idle_close_by_peer_total 27969
telemt_me_route_drop_no_conn_total 49293
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129635
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
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 26823
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 26147
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 658
telemt_user_connections_total{user="hello"} 134462
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 1768368797 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 64103433015 (59.70 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 148445.5 (41h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872345
telemt_connections_bad_total 27386
telemt_handshake_timeouts_total 25308
telemt_upstream_connect_attempt_total 30563
telemt_upstream_connect_success_total 30398
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 30563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 3408
telemt_me_reconnect_attempts_total 27721
telemt_me_reconnect_success_total 23056
telemt_me_reader_eof_total 24711
telemt_me_idle_close_by_peer_total 24708
telemt_me_route_drop_no_conn_total 415542
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 815012
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
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 23504
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23049
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 787768
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 14078724552 (13.11 GB)
telemt_user_octets_to_client{user="hello"} 404359533808 (376.59 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 34
```