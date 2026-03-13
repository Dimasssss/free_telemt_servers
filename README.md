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

# Server Metrics 2026-03-13 14:19:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 110751.3 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457793
telemt_connections_bad_total 3217
telemt_handshake_timeouts_total 8546
telemt_upstream_connect_attempt_total 27881
telemt_upstream_connect_success_total 27751
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 27881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2426
telemt_me_reconnect_attempts_total 25739
telemt_me_reconnect_success_total 22209
telemt_me_reader_eof_total 23720
telemt_me_idle_close_by_peer_total 23719
telemt_me_route_drop_no_conn_total 148373
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400459
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1339
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 486
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 22550
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22193
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 341
telemt_user_connections_total{user="hello"} 400037
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 7224882952 (6.73 GB)
telemt_user_octets_to_client{user="hello"} 184945761940 (172.24 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 110645.0 (30h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215743
telemt_connections_bad_total 1785
telemt_handshake_timeouts_total 1540
telemt_upstream_connect_attempt_total 74912
telemt_upstream_connect_success_total 74167
telemt_upstream_connect_fail_total 745
telemt_upstream_connect_attempts_per_request{bucket="1"} 74912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 715
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 745
telemt_me_keepalive_timeout_total 1396
telemt_me_reconnect_attempts_total 106674
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29302
telemt_me_idle_close_by_peer_total 29302
telemt_me_route_drop_no_conn_total 79988
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161428
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 25
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
telemt_me_writer_removed_unexpected_total 28766
telemt_me_refill_failed_total 2516
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2744
telemt_user_connections_total{user="hello"} 203844
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 2057748909 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 65624338127 (61.12 GB)
telemt_user_msgs_from_client{user="hello"} 628730
telemt_user_msgs_to_client{user="hello"} 4326823
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 110608.8 (30h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261993
telemt_connections_bad_total 2156
telemt_handshake_timeouts_total 11008
telemt_upstream_connect_attempt_total 29679
telemt_upstream_connect_success_total 29675
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2284
telemt_me_reconnect_attempts_total 25330
telemt_me_reconnect_success_total 24114
telemt_me_reader_eof_total 25835
telemt_me_idle_close_by_peer_total 25835
telemt_me_route_drop_no_conn_total 95249
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239453
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 24376
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24094
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 239367
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 9491928760 (8.84 GB)
telemt_user_octets_to_client{user="hello"} 101857469092 (94.86 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 110584.2 (30h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360561
telemt_connections_bad_total 15043
telemt_handshake_timeouts_total 3542
telemt_upstream_connect_attempt_total 41670
telemt_upstream_connect_success_total 31546
telemt_upstream_connect_fail_total 10124
telemt_upstream_connect_attempts_per_request{bucket="1"} 41670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10124
telemt_me_keepalive_timeout_total 4137
telemt_me_reconnect_attempts_total 96808
telemt_me_reconnect_success_total 22979
telemt_me_reader_eof_total 25984
telemt_me_idle_close_by_peer_total 25977
telemt_me_route_drop_no_conn_total 129155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311316
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1183
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 831
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 25582
telemt_me_refill_failed_total 2302
telemt_me_writer_restored_same_endpoint_total 22969
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2603
telemt_user_connections_total{user="hello"} 314228
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 6801303374 (6.33 GB)
telemt_user_octets_to_client{user="hello"} 117931977129 (109.83 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 60755.8 (16h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92521
telemt_connections_bad_total 12238
telemt_handshake_timeouts_total 1207
telemt_upstream_connect_attempt_total 25225
telemt_upstream_connect_success_total 25020
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 25225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 1025
telemt_me_reconnect_attempts_total 26984
telemt_me_reconnect_success_total 17063
telemt_me_reader_eof_total 18308
telemt_me_idle_close_by_peer_total 18308
telemt_me_route_drop_no_conn_total 27524
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71222
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 248
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 17520
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17045
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 76122
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 909498405 (867.37 MB)
telemt_user_octets_to_client{user="hello"} 22248141547 (20.72 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 110541.2 (30h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 649491
telemt_connections_bad_total 17998
telemt_handshake_timeouts_total 19573
telemt_upstream_connect_attempt_total 23252
telemt_upstream_connect_success_total 23134
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2528
telemt_me_reconnect_attempts_total 22273
telemt_me_reconnect_success_total 17648
telemt_me_reader_eof_total 18946
telemt_me_idle_close_by_peer_total 18943
telemt_me_route_drop_no_conn_total 313921
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 617231
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 475
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 18021
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17641
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 590179
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 10249755052 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 310025241908 (288.73 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 80
```