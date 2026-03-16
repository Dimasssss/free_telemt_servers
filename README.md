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

# Server Metrics 2026-03-16 09:21:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 126395.4 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604615
telemt_connections_bad_total 9785
telemt_handshake_timeouts_total 21303
telemt_upstream_connect_attempt_total 29673
telemt_upstream_connect_success_total 29532
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 29673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 27924
telemt_me_reconnect_success_total 23267
telemt_me_reader_eof_total 24886
telemt_me_idle_close_by_peer_total 24886
telemt_me_route_drop_no_conn_total 536632
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 593997
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2792
telemt_desync_full_logged_total 1089
telemt_desync_suppressed_total 1703
telemt_desync_frames_bucket_total{bucket="1_2"} 616
telemt_desync_frames_bucket_total{bucket="3_10"} 1073
telemt_desync_frames_bucket_total{bucket="gt_10"} 1103
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23668
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 23233
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 532767
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 10460057816 (9.74 GB)
telemt_user_octets_to_client{user="hello"} 334525557692 (311.55 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 126402.5 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248240
telemt_connections_bad_total 3290
telemt_handshake_timeouts_total 15460
telemt_upstream_connect_attempt_total 33894
telemt_upstream_connect_success_total 33819
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 33894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 680
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 36425
telemt_me_reconnect_success_total 27134
telemt_me_reader_eof_total 29089
telemt_me_idle_close_by_peer_total 29088
telemt_me_route_drop_no_conn_total 119056
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220894
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 190
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27802
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 27118
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 668
telemt_user_connections_total{user="hello"} 220437
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 4914975241 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 121403111348 (113.07 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 126395.6 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258636
telemt_connections_bad_total 5756
telemt_handshake_timeouts_total 5506
telemt_upstream_connect_attempt_total 35177
telemt_upstream_connect_success_total 35169
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 35177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 36243
telemt_me_reconnect_success_total 28827
telemt_me_reader_eof_total 31009
telemt_me_idle_close_by_peer_total 31008
telemt_me_route_drop_no_conn_total 89653
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209012
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 29344
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 28819
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 208713
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 17651879461 (16.44 GB)
telemt_user_octets_to_client{user="hello"} 116909110756 (108.88 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 126394.8 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368661
telemt_connections_bad_total 1380
telemt_handshake_timeouts_total 3175
telemt_upstream_connect_attempt_total 29233
telemt_upstream_connect_success_total 29195
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 29233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 23060
telemt_me_reconnect_success_total 22907
telemt_me_reader_eof_total 24448
telemt_me_idle_close_by_peer_total 24447
telemt_me_route_drop_no_conn_total 128374
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340716
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1265
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 830
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 540
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23215
telemt_me_writer_restored_same_endpoint_total 22896
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 340591
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 5832345622 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 139685177652 (130.09 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 101466.2 (28h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233943
telemt_connections_bad_total 37067
telemt_handshake_timeouts_total 4235
telemt_upstream_connect_attempt_total 28992
telemt_upstream_connect_success_total 28834
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 28992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 118132
telemt_me_reconnect_success_total 23631
telemt_me_reader_eof_total 25089
telemt_me_idle_close_by_peer_total 25089
telemt_me_route_drop_no_conn_total 73188
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185959
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 597
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 23834
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 23527
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 185575
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2452711165 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 80102551915 (74.60 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 126394.3 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 851626
telemt_connections_bad_total 72548
telemt_handshake_timeouts_total 9900
telemt_upstream_connect_attempt_total 26508
telemt_upstream_connect_success_total 26368
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 26508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 21423
telemt_me_reconnect_success_total 20071
telemt_me_reader_eof_total 21419
telemt_me_idle_close_by_peer_total 21419
telemt_me_route_drop_no_conn_total 660286
telemt_me_route_drop_channel_closed_total 116
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 842676
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20352
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 20044
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 701299
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 15089061544 (14.05 GB)
telemt_user_octets_to_client{user="hello"} 424560544296 (395.40 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 88
```