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

# Server Metrics 2026-03-17 15:25:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 74410.1 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818535
telemt_connections_bad_total 6075
telemt_handshake_timeouts_total 23898
telemt_upstream_connect_attempt_total 17721
telemt_upstream_connect_success_total 17260
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 17721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 25934
telemt_me_reconnect_success_total 11230
telemt_me_reader_eof_total 12244
telemt_me_idle_close_by_peer_total 12243
telemt_me_route_drop_no_conn_total 342745
telemt_me_route_drop_channel_closed_total 84
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 743777
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5174
telemt_desync_full_logged_total 1435
telemt_desync_suppressed_total 3739
telemt_desync_frames_bucket_total{bucket="1_2"} 1499
telemt_desync_frames_bucket_total{bucket="3_10"} 2046
telemt_desync_frames_bucket_total{bucket="gt_10"} 1629
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11842
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11208
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 745617
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 11982440143 (11.16 GB)
telemt_user_octets_to_client{user="hello"} 247083691743 (230.11 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 74661.2 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533849
telemt_connections_bad_total 31816
telemt_handshake_timeouts_total 27084
telemt_upstream_connect_attempt_total 99368
telemt_upstream_connect_success_total 98832
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 99368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 38721
telemt_me_reconnect_success_total 13462
telemt_me_reader_eof_total 14805
telemt_me_idle_close_by_peer_total 14805
telemt_me_route_drop_no_conn_total 192937
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368552
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1479
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 1014
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14414
telemt_me_refill_failed_total 785
telemt_me_writer_restored_same_endpoint_total 13446
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 952
telemt_user_connections_total{user="hello"} 450088
telemt_user_connections_current{user="hello"} 772
telemt_user_octets_from_client{user="hello"} 5022018401 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 130203994750 (121.26 GB)
telemt_user_msgs_from_client{user="hello"} 1209459
telemt_user_msgs_to_client{user="hello"} 4206964
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 74437.1 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274944
telemt_connections_bad_total 7838
telemt_handshake_timeouts_total 18345
telemt_upstream_connect_attempt_total 19447
telemt_upstream_connect_success_total 19345
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 19447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 29355
telemt_me_reconnect_success_total 15566
telemt_me_reader_eof_total 16860
telemt_me_idle_close_by_peer_total 16857
telemt_me_route_drop_no_conn_total 129260
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234652
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16205
telemt_me_refill_failed_total 428
telemt_me_writer_restored_same_endpoint_total 15555
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 639
telemt_user_connections_total{user="hello"} 234511
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 18343212596 (17.08 GB)
telemt_user_octets_to_client{user="hello"} 57833047044 (53.86 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 74496.4 (20h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 636354
telemt_connections_bad_total 8668
telemt_handshake_timeouts_total 13765
telemt_upstream_connect_attempt_total 25659
telemt_upstream_connect_success_total 25457
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 25659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 28110
telemt_me_reconnect_success_total 11951
telemt_me_reader_eof_total 13105
telemt_me_idle_close_by_peer_total 13104
telemt_me_route_drop_no_conn_total 252743
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539229
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1864
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 836
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12664
telemt_me_refill_failed_total 500
telemt_me_writer_restored_same_endpoint_total 11942
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 713
telemt_user_connections_total{user="hello"} 548775
telemt_user_connections_current{user="hello"} 796
telemt_user_octets_from_client{user="hello"} 6628021508 (6.17 GB)
telemt_user_octets_to_client{user="hello"} 169561542952 (157.92 GB)
telemt_user_msgs_from_client{user="hello"} 84787
telemt_user_msgs_to_client{user="hello"} 411722
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 74468.4 (20h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295183
telemt_connections_bad_total 57526
telemt_handshake_timeouts_total 3698
telemt_upstream_connect_attempt_total 21425
telemt_upstream_connect_success_total 20951
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 21425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 42661
telemt_me_reconnect_success_total 16813
telemt_me_reader_eof_total 18210
telemt_me_idle_close_by_peer_total 18208
telemt_me_route_drop_no_conn_total 83750
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221561
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17900
telemt_me_refill_failed_total 803
telemt_me_writer_restored_same_endpoint_total 16805
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1087
telemt_user_connections_total{user="hello"} 222070
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 2750208807 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 80844043307 (75.29 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 74631.4 (20h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 717112
telemt_connections_bad_total 57587
telemt_handshake_timeouts_total 7022
telemt_upstream_connect_attempt_total 15008
telemt_upstream_connect_success_total 14926
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7591
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 21483
telemt_me_reconnect_success_total 11187
telemt_me_reader_eof_total 12177
telemt_me_idle_close_by_peer_total 12177
telemt_me_route_drop_no_conn_total 523598
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728843
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1073
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 694
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 385
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11683
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11173
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 616232
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 9042203856 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 275432854652 (256.52 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 22396.5 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17346
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 12058
telemt_upstream_connect_success_total 11959
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 12058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 22226
telemt_me_reconnect_success_total 10667
telemt_me_reader_eof_total 11306
telemt_me_idle_close_by_peer_total 11306
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 6403
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16530
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 11135
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 10652
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 16628
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 513682573 (489.89 MB)
telemt_user_octets_to_client{user="hello"} 23862658638 (22.22 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 12
```