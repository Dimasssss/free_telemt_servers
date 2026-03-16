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

# Server Metrics 2026-03-16 13:31:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 141418.7 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806585
telemt_connections_bad_total 54287
telemt_handshake_timeouts_total 26889
telemt_upstream_connect_attempt_total 32666
telemt_upstream_connect_success_total 32508
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 32666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 39689
telemt_me_reconnect_success_total 25453
telemt_me_reader_eof_total 27441
telemt_me_idle_close_by_peer_total 27441
telemt_me_route_drop_no_conn_total 621815
telemt_me_route_drop_channel_closed_total 99
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738562
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3509
telemt_desync_full_logged_total 1316
telemt_desync_suppressed_total 2193
telemt_desync_frames_bucket_total{bucket="1_2"} 752
telemt_desync_frames_bucket_total{bucket="3_10"} 1459
telemt_desync_frames_bucket_total{bucket="gt_10"} 1298
telemt_pool_swap_total 127
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26181
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 25418
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 728
telemt_user_connections_total{user="hello"} 675030
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 13936998092 (12.98 GB)
telemt_user_octets_to_client{user="hello"} 383303015380 (356.98 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 141426.3 (39h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379983
telemt_connections_bad_total 41521
telemt_handshake_timeouts_total 22246
telemt_upstream_connect_attempt_total 37655
telemt_upstream_connect_success_total 37548
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 37655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 906
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 46441
telemt_me_reconnect_success_total 29861
telemt_me_reader_eof_total 32122
telemt_me_idle_close_by_peer_total 32121
telemt_me_route_drop_no_conn_total 160345
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303760
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 268
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 179
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30807
telemt_me_refill_failed_total 508
telemt_me_writer_restored_same_endpoint_total 29845
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 946
telemt_user_connections_total{user="hello"} 303420
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 5931016221 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 144570295204 (134.64 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 141418.6 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324437
telemt_connections_bad_total 8736
telemt_handshake_timeouts_total 9090
telemt_upstream_connect_attempt_total 38981
telemt_upstream_connect_success_total 38971
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 38981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 39286
telemt_me_reconnect_success_total 31831
telemt_me_reader_eof_total 34159
telemt_me_idle_close_by_peer_total 34158
telemt_me_route_drop_no_conn_total 109544
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264804
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 32389
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31823
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 264393
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 19238943509 (17.92 GB)
telemt_user_octets_to_client{user="hello"} 133830679952 (124.64 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 141418.2 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 501557
telemt_connections_bad_total 5613
telemt_handshake_timeouts_total 6693
telemt_upstream_connect_attempt_total 32819
telemt_upstream_connect_success_total 32767
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 32819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 33292
telemt_me_reconnect_success_total 25685
telemt_me_reader_eof_total 27540
telemt_me_idle_close_by_peer_total 27539
telemt_me_route_drop_no_conn_total 166532
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457825
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 1094
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 26270
telemt_me_refill_failed_total 232
telemt_me_writer_restored_same_endpoint_total 25674
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 457623
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 6936963494 (6.46 GB)
telemt_user_octets_to_client{user="hello"} 169985202720 (158.31 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 116489.7 (32h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309292
telemt_connections_bad_total 57941
telemt_handshake_timeouts_total 6317
telemt_upstream_connect_attempt_total 33199
telemt_upstream_connect_success_total 33019
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 33199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 123743
telemt_me_reconnect_success_total 27033
telemt_me_reader_eof_total 28712
telemt_me_idle_close_by_peer_total 28712
telemt_me_route_drop_no_conn_total 91236
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235701
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 722
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 546
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 27346
telemt_me_refill_failed_total 3101
telemt_me_writer_restored_same_endpoint_total 26929
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 235302
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 3066860181 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 109162706527 (101.67 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 141418.0 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1037330
telemt_connections_bad_total 78810
telemt_handshake_timeouts_total 13137
telemt_upstream_connect_attempt_total 30012
telemt_upstream_connect_success_total 29855
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 30012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15784
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 26417
telemt_me_reconnect_success_total 22763
telemt_me_reader_eof_total 24299
telemt_me_idle_close_by_peer_total 24298
telemt_me_route_drop_no_conn_total 732197
telemt_me_route_drop_channel_closed_total 145
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1005413
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 23152
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 22736
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 863985
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 18224731040 (16.97 GB)
telemt_user_octets_to_client{user="hello"} 489791269404 (456.15 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 106
```