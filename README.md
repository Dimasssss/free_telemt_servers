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

# Server Metrics 2026-03-14 00:56:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 148962.7 (41h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592834
telemt_connections_bad_total 21285
telemt_handshake_timeouts_total 12854
telemt_upstream_connect_attempt_total 37917
telemt_upstream_connect_success_total 37729
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 37917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5477
telemt_me_reconnect_attempts_total 34576
telemt_me_reconnect_success_total 29904
telemt_me_reader_eof_total 31954
telemt_me_idle_close_by_peer_total 31953
telemt_me_route_drop_no_conn_total 194778
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507774
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 561
telemt_desync_suppressed_total 1079
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 615
telemt_desync_frames_bucket_total{bucket="gt_10"} 672
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 30380
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 29888
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 507669
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 15476390266 (14.41 GB)
telemt_user_octets_to_client{user="hello"} 250931429420 (233.70 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 148855.4 (41h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304361
telemt_connections_bad_total 2235
telemt_handshake_timeouts_total 1932
telemt_upstream_connect_attempt_total 142598
telemt_upstream_connect_success_total 141500
telemt_upstream_connect_fail_total 1098
telemt_upstream_connect_attempts_per_request{bucket="1"} 142598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1098
telemt_me_keepalive_timeout_total 3781
telemt_me_reconnect_attempts_total 160380
telemt_me_reconnect_success_total 30748
telemt_me_reader_eof_total 35589
telemt_me_idle_close_by_peer_total 35589
telemt_me_route_drop_no_conn_total 93985
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185440
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
telemt_me_writer_removed_unexpected_total 35084
telemt_me_refill_failed_total 4045
telemt_me_writer_restored_same_endpoint_total 30731
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4336
telemt_user_connections_total{user="hello"} 288552
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 3025096467 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 90249967547 (84.05 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 148819.2 (41h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356122
telemt_connections_bad_total 2774
telemt_handshake_timeouts_total 33209
telemt_upstream_connect_attempt_total 39496
telemt_upstream_connect_success_total 39490
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 39496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3251
telemt_me_reconnect_attempts_total 33277
telemt_me_reconnect_success_total 32014
telemt_me_reader_eof_total 34393
telemt_me_idle_close_by_peer_total 34393
telemt_me_route_drop_no_conn_total 126291
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307697
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
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 32392
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 31994
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 378
telemt_user_connections_total{user="hello"} 307598
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 12584952412 (11.72 GB)
telemt_user_octets_to_client{user="hello"} 126378786780 (117.70 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 148794.8 (41h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457546
telemt_connections_bad_total 15364
telemt_handshake_timeouts_total 4319
telemt_upstream_connect_attempt_total 67669
telemt_upstream_connect_success_total 57236
telemt_upstream_connect_fail_total 10433
telemt_upstream_connect_attempts_per_request{bucket="1"} 67669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10433
telemt_me_keepalive_timeout_total 5051
telemt_me_reconnect_attempts_total 135749
telemt_me_reconnect_success_total 30772
telemt_me_reader_eof_total 34955
telemt_me_idle_close_by_peer_total 34947
telemt_me_route_drop_no_conn_total 161230
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387545
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
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 34425
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 30762
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3653
telemt_user_connections_total{user="hello"} 406387
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 9053326355 (8.43 GB)
telemt_user_octets_to_client{user="hello"} 155234415584 (144.57 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 98966.4 (27h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165819
telemt_connections_bad_total 24225
telemt_handshake_timeouts_total 1553
telemt_upstream_connect_attempt_total 36412
telemt_upstream_connect_success_total 36083
telemt_upstream_connect_fail_total 329
telemt_upstream_connect_attempts_per_request{bucket="1"} 36412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 329
telemt_me_keepalive_timeout_total 1359
telemt_me_reconnect_attempts_total 39679
telemt_me_reconnect_success_total 26267
telemt_me_reader_eof_total 28071
telemt_me_idle_close_by_peer_total 28071
telemt_me_route_drop_no_conn_total 49403
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130306
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
telemt_me_writer_removed_unexpected_total 26925
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 26249
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 658
telemt_user_connections_total{user="hello"} 135126
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 1782016205 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 64124096971 (59.72 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 148750.9 (41h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 873266
telemt_connections_bad_total 27386
telemt_handshake_timeouts_total 25315
telemt_upstream_connect_attempt_total 30666
telemt_upstream_connect_success_total 30500
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 30666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 3410
telemt_me_reconnect_attempts_total 27779
telemt_me_reconnect_success_total 23114
telemt_me_reader_eof_total 24776
telemt_me_idle_close_by_peer_total 24773
telemt_me_route_drop_no_conn_total 415844
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 815902
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
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 23562
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23107
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 788658
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 14083672204 (13.12 GB)
telemt_user_octets_to_client{user="hello"} 404448333288 (376.67 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 29
```