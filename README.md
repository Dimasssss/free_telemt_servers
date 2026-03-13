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

# Server Metrics 2026-03-13 16:36:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 119019.4 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496731
telemt_connections_bad_total 4552
telemt_handshake_timeouts_total 8949
telemt_upstream_connect_attempt_total 29617
telemt_upstream_connect_success_total 29473
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 29617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2600
telemt_me_reconnect_attempts_total 27047
telemt_me_reconnect_success_total 23505
telemt_me_reader_eof_total 25118
telemt_me_idle_close_by_peer_total 25117
telemt_me_route_drop_no_conn_total 162418
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435878
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1400
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 909
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 590
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23867
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23489
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 435452
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 7693355640 (7.16 GB)
telemt_user_octets_to_client{user="hello"} 202232683664 (188.34 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 118912.3 (33h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241893
telemt_connections_bad_total 1885
telemt_handshake_timeouts_total 1757
telemt_upstream_connect_attempt_total 97707
telemt_upstream_connect_success_total 96895
telemt_upstream_connect_fail_total 812
telemt_upstream_connect_attempts_per_request{bucket="1"} 97707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 812
telemt_me_keepalive_timeout_total 1446
telemt_me_reconnect_attempts_total 119072
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29694
telemt_me_idle_close_by_peer_total 29694
telemt_me_route_drop_no_conn_total 81869
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164218
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 29
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
telemt_me_writer_removed_unexpected_total 29164
telemt_me_refill_failed_total 2903
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3131
telemt_user_connections_total{user="hello"} 228912
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 2412920382 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 71255659762 (66.36 GB)
telemt_user_msgs_from_client{user="hello"} 1019187
telemt_user_msgs_to_client{user="hello"} 6035052
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 118876.0 (33h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289041
telemt_connections_bad_total 2446
telemt_handshake_timeouts_total 14569
telemt_upstream_connect_attempt_total 31830
telemt_upstream_connect_success_total 31825
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2461
telemt_me_reconnect_attempts_total 27054
telemt_me_reconnect_success_total 25830
telemt_me_reader_eof_total 27668
telemt_me_idle_close_by_peer_total 27668
telemt_me_route_drop_no_conn_total 103937
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261788
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 26119
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25810
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 261700
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 10093109688 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 109876730360 (102.33 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 118851.5 (33h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392041
telemt_connections_bad_total 15068
telemt_handshake_timeouts_total 3829
telemt_upstream_connect_attempt_total 46840
telemt_upstream_connect_success_total 36640
telemt_upstream_connect_fail_total 10199
telemt_upstream_connect_attempts_per_request{bucket="1"} 46839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10199
telemt_me_keepalive_timeout_total 4179
telemt_me_reconnect_attempts_total 108488
telemt_me_reconnect_success_total 24286
telemt_me_reader_eof_total 27625
telemt_me_idle_close_by_peer_total 27618
telemt_me_route_drop_no_conn_total 139265
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337716
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27225
telemt_me_refill_failed_total 2626
telemt_me_writer_restored_same_endpoint_total 24276
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2939
telemt_user_connections_total{user="hello"} 344008
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 8064293645 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 126371575507 (117.69 GB)
telemt_user_msgs_from_client{user="hello"} 261389
telemt_user_msgs_to_client{user="hello"} 284453
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 69023.1 (19h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110183
telemt_connections_bad_total 14370
telemt_handshake_timeouts_total 1366
telemt_upstream_connect_attempt_total 27625
telemt_upstream_connect_success_total 27379
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 27625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 1104
telemt_me_reconnect_attempts_total 30201
telemt_me_reconnect_success_total 19025
telemt_me_reader_eof_total 20383
telemt_me_idle_close_by_peer_total 20383
telemt_me_route_drop_no_conn_total 33853
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86020
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 19539
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 19007
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 90919
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 1038879901 (990.75 MB)
telemt_user_octets_to_client{user="hello"} 28342697515 (26.40 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 118809.3 (33h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 724053
telemt_connections_bad_total 24640
telemt_handshake_timeouts_total 24034
telemt_upstream_connect_attempt_total 24777
telemt_upstream_connect_success_total 24652
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 24777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 2623
telemt_me_reconnect_attempts_total 23399
telemt_me_reconnect_success_total 18767
telemt_me_reader_eof_total 20137
telemt_me_idle_close_by_peer_total 20134
telemt_me_route_drop_no_conn_total 341966
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678797
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19150
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18760
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 651687
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 11339742716 (10.56 GB)
telemt_user_octets_to_client{user="hello"} 332181824932 (309.37 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 86
```