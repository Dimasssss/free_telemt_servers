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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 11:20:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 48715.1 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155651
telemt_connections_bad_total 97646
telemt_connections_current 1585
telemt_connections_me_current 1585
telemt_handshake_timeouts_total 40346
telemt_upstream_connect_attempt_total 9393
telemt_upstream_connect_success_total 9231
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 9393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 8646
telemt_me_reconnect_success_total 6761
telemt_me_reader_eof_total 7147
telemt_me_idle_close_by_peer_total 7144
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 486424
telemt_me_route_drop_channel_closed_total 178
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901731
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5016
telemt_desync_full_logged_total 1531
telemt_desync_suppressed_total 3485
telemt_desync_frames_bucket_total{bucket="1_2"} 1642
telemt_desync_frames_bucket_total{bucket="3_10"} 1823
telemt_desync_frames_bucket_total{bucket="gt_10"} 1551
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6916
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 6740
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 895671
telemt_user_connections_current{user="hello"} 1585
telemt_user_octets_from_client{user="hello"} 13646908096 (12.71 GB)
telemt_user_octets_to_client{user="hello"} 274335499512 (255.49 GB)
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 48719.5 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3063967
telemt_connections_bad_total 183071
telemt_connections_current 3862
telemt_connections_me_current 3862
telemt_handshake_timeouts_total 58832
telemt_upstream_connect_attempt_total 9270
telemt_upstream_connect_success_total 9100
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 9270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 12842
telemt_me_reconnect_success_total 6610
telemt_me_reader_eof_total 7121
telemt_me_idle_close_by_peer_total 7120
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 2109311
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2583274
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10491
telemt_desync_full_logged_total 3511
telemt_desync_suppressed_total 6980
telemt_desync_frames_bucket_total{bucket="1_2"} 2019
telemt_desync_frames_bucket_total{bucket="3_10"} 4135
telemt_desync_frames_bucket_total{bucket="gt_10"} 4337
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6921
telemt_me_refill_failed_total 194
telemt_me_writer_restored_same_endpoint_total 6588
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 2582887
telemt_user_connections_current{user="hello"} 3862
telemt_user_octets_from_client{user="hello"} 35617202108 (33.17 GB)
telemt_user_octets_to_client{user="hello"} 815277039956 (759.29 GB)
telemt_user_unique_ips_current{user="hello"} 1364
telemt_user_unique_ips_recent_window{user="hello"} 644
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 48784.8 (13h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2413726
telemt_connections_bad_total 130311
telemt_connections_current 3211
telemt_connections_me_current 3211
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 62707
telemt_upstream_connect_attempt_total 17097
telemt_upstream_connect_success_total 16928
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 17097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10607
telemt_me_reconnect_success_total 6269
telemt_me_reader_eof_total 6684
telemt_me_idle_close_by_peer_total 6683
telemt_me_route_drop_no_conn_total 1232307
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1835482
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6785
telemt_desync_full_logged_total 2280
telemt_desync_suppressed_total 4505
telemt_desync_frames_bucket_total{bucket="1_2"} 1425
telemt_desync_frames_bucket_total{bucket="3_10"} 2659
telemt_desync_frames_bucket_total{bucket="gt_10"} 2701
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6733
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6245
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1841648
telemt_user_connections_current{user="hello"} 3211
telemt_user_octets_from_client{user="hello"} 21361977940 (19.89 GB)
telemt_user_octets_to_client{user="hello"} 529485072362 (493.12 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1037
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 48713.2 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2914107
telemt_connections_bad_total 646639
telemt_connections_current 3696
telemt_connections_me_current 3696
telemt_handshake_timeouts_total 57026
telemt_upstream_connect_attempt_total 8629
telemt_upstream_connect_success_total 8565
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 8629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7293
telemt_me_reconnect_success_total 6088
telemt_me_reader_eof_total 6475
telemt_me_idle_close_by_peer_total 6474
telemt_me_route_drop_no_conn_total 1076674
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1917908
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8394
telemt_desync_full_logged_total 2610
telemt_desync_suppressed_total 5784
telemt_desync_frames_bucket_total{bucket="1_2"} 1602
telemt_desync_frames_bucket_total{bucket="3_10"} 3633
telemt_desync_frames_bucket_total{bucket="gt_10"} 3159
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6217
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6064
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 1916987
telemt_user_connections_current{user="hello"} 3696
telemt_user_octets_from_client{user="hello"} 33440746820 (31.14 GB)
telemt_user_octets_to_client{user="hello"} 775401527308 (722.15 GB)
telemt_user_unique_ips_current{user="hello"} 1219
telemt_user_unique_ips_recent_window{user="hello"} 583
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 48726.8 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 501562
telemt_connections_bad_total 18590
telemt_connections_current 926
telemt_connections_me_current 926
telemt_handshake_timeouts_total 3912
telemt_upstream_connect_attempt_total 12190
telemt_upstream_connect_success_total 11881
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 12190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 16986
telemt_me_reconnect_success_total 9398
telemt_me_reader_eof_total 10017
telemt_me_idle_close_by_peer_total 10017
telemt_me_route_drop_no_conn_total 259750
telemt_me_route_drop_channel_closed_total 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 454433
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 970
telemt_desync_full_logged_total 335
telemt_desync_suppressed_total 635
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 380
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9720
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9367
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 454376
telemt_user_connections_current{user="hello"} 926
telemt_user_octets_from_client{user="hello"} 7342013376 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 168958401668 (157.35 GB)
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 48715.6 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2042815
telemt_connections_bad_total 173072
telemt_connections_current 2975
telemt_connections_me_current 2975
telemt_handshake_timeouts_total 72184
telemt_upstream_connect_attempt_total 9815
telemt_upstream_connect_success_total 9814
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4488
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8685
telemt_me_reconnect_success_total 7318
telemt_me_reader_eof_total 7744
telemt_me_idle_close_by_peer_total 7743
telemt_me_route_drop_no_conn_total 1043415
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1701208
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9212
telemt_desync_full_logged_total 2970
telemt_desync_suppressed_total 6242
telemt_desync_frames_bucket_total{bucket="1_2"} 1751
telemt_desync_frames_bucket_total{bucket="3_10"} 3524
telemt_desync_frames_bucket_total{bucket="gt_10"} 3937
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7454
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7303
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 1699911
telemt_user_connections_current{user="hello"} 2975
telemt_user_octets_from_client{user="hello"} 22565679784 (21.02 GB)
telemt_user_octets_to_client{user="hello"} 754630834624 (702.80 GB)
telemt_user_unique_ips_current{user="hello"} 972
telemt_user_unique_ips_recent_window{user="hello"} 434
```