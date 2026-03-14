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

# Server Metrics 2026-03-14 08:54:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 177682.4 (49h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 685736
telemt_connections_bad_total 32583
telemt_handshake_timeouts_total 13370
telemt_upstream_connect_attempt_total 45135
telemt_upstream_connect_success_total 44906
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 45135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5783
telemt_me_reconnect_attempts_total 40368
telemt_me_reconnect_success_total 35670
telemt_me_reader_eof_total 38141
telemt_me_idle_close_by_peer_total 38140
telemt_me_route_drop_no_conn_total 226657
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2262
telemt_desync_full_logged_total 768
telemt_desync_suppressed_total 1494
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 948
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 36197
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35650
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 585597
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 17030374926 (15.86 GB)
telemt_user_octets_to_client{user="hello"} 280920553372 (261.63 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 177575.3 (49h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344852
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 3031
telemt_upstream_connect_attempt_total 152650
telemt_upstream_connect_success_total 151322
telemt_upstream_connect_fail_total 1328
telemt_upstream_connect_attempts_per_request{bucket="1"} 152650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2439
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1328
telemt_me_keepalive_timeout_total 5337
telemt_me_reconnect_attempts_total 182002
telemt_me_reconnect_success_total 39157
telemt_me_reader_eof_total 44672
telemt_me_idle_close_by_peer_total 44672
telemt_me_route_drop_no_conn_total 115990
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222231
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 44
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 43998
telemt_me_refill_failed_total 4457
telemt_me_writer_restored_same_endpoint_total 39140
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4841
telemt_user_connections_total{user="hello"} 325337
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 3377799479 (3.15 GB)
telemt_user_octets_to_client{user="hello"} 105006718727 (97.80 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 177539.1 (49h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402506
telemt_connections_bad_total 3199
telemt_handshake_timeouts_total 35589
telemt_upstream_connect_attempt_total 47148
telemt_upstream_connect_success_total 47139
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3518
telemt_me_reconnect_attempts_total 39532
telemt_me_reconnect_success_total 38238
telemt_me_reader_eof_total 41099
telemt_me_idle_close_by_peer_total 41099
telemt_me_route_drop_no_conn_total 145504
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349541
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 128
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 38701
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38217
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 349301
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 13697246920 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 149890031544 (139.60 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 177514.5 (49h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505392
telemt_connections_bad_total 16440
telemt_handshake_timeouts_total 4597
telemt_upstream_connect_attempt_total 77294
telemt_upstream_connect_success_total 66656
telemt_upstream_connect_fail_total 10638
telemt_upstream_connect_attempts_per_request{bucket="1"} 77294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10638
telemt_me_keepalive_timeout_total 5487
telemt_me_reconnect_attempts_total 149891
telemt_me_reconnect_success_total 38767
telemt_me_reader_eof_total 43488
telemt_me_idle_close_by_peer_total 43480
telemt_me_route_drop_no_conn_total 183270
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 431736
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1898
telemt_desync_full_logged_total 560
telemt_desync_suppressed_total 1338
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 734
telemt_desync_frames_bucket_total{bucket="gt_10"} 718
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 42684
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 38757
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3917
telemt_user_connections_total{user="hello"} 450617
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 9730223907 (9.06 GB)
telemt_user_octets_to_client{user="hello"} 188168658244 (175.25 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 127686.2 (35h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210047
telemt_connections_bad_total 32164
telemt_handshake_timeouts_total 1775
telemt_upstream_connect_attempt_total 44976
telemt_upstream_connect_success_total 44544
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 44976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_timeout_total 2577
telemt_me_reconnect_attempts_total 48036
telemt_me_reconnect_success_total 33317
telemt_me_reader_eof_total 35657
telemt_me_idle_close_by_peer_total 35657
telemt_me_route_drop_no_conn_total 63191
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165500
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 718
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 34078
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 33299
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 170262
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 2493215925 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 81135465779 (75.56 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 177470.8 (49h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1022498
telemt_connections_bad_total 36391
telemt_handshake_timeouts_total 26458
telemt_upstream_connect_attempt_total 36997
telemt_upstream_connect_success_total 36799
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 36997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 4763
telemt_me_reconnect_attempts_total 32691
telemt_me_reconnect_success_total 28008
telemt_me_reader_eof_total 30052
telemt_me_idle_close_by_peer_total 30049
telemt_me_route_drop_no_conn_total 480362
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 947596
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 792
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 28507
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28001
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 920222
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 15549629556 (14.48 GB)
telemt_user_octets_to_client{user="hello"} 458751769720 (427.25 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 70
```