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

# Server Metrics 2026-03-18 06:07:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 127306.9 (35h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1539130
telemt_connections_bad_total 10689
telemt_handshake_timeouts_total 35961
telemt_upstream_connect_attempt_total 27671
telemt_upstream_connect_success_total 27152
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 27671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 35676
telemt_me_reconnect_success_total 18524
telemt_me_reader_eof_total 20081
telemt_me_idle_close_by_peer_total 20080
telemt_me_route_drop_no_conn_total 622310
telemt_me_route_drop_channel_closed_total 170
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1353818
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8272
telemt_desync_full_logged_total 2491
telemt_desync_suppressed_total 5781
telemt_desync_frames_bucket_total{bucket="1_2"} 2168
telemt_desync_frames_bucket_total{bucket="3_10"} 3179
telemt_desync_frames_bucket_total{bucket="gt_10"} 2925
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 19337
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18502
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 813
telemt_user_connections_total{user="hello"} 1348034
telemt_user_connections_current{user="hello"} 1016
telemt_user_octets_from_client{user="hello"} 32177362071 (29.97 GB)
telemt_user_octets_to_client{user="hello"} 484891189699 (451.59 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 127558.4 (35h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1654494
telemt_connections_bad_total 79455
telemt_handshake_timeouts_total 53518
telemt_upstream_connect_attempt_total 471130
telemt_upstream_connect_success_total 469494
telemt_upstream_connect_fail_total 1636
telemt_upstream_connect_attempts_per_request{bucket="1"} 471130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1636
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126967
telemt_me_reconnect_success_total 20235
telemt_me_reader_eof_total 22541
telemt_me_idle_close_by_peer_total 22528
telemt_me_route_drop_no_conn_total 438354
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1000476
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4571
telemt_desync_full_logged_total 1583
telemt_desync_suppressed_total 2988
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1838
telemt_desync_frames_bucket_total{bucket="gt_10"} 1841
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 21866
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20217
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1631
telemt_user_connections_total{user="hello"} 1442832
telemt_user_connections_current{user="hello"} 1888
telemt_user_octets_from_client{user="hello"} 20067042261 (18.69 GB)
telemt_user_octets_to_client{user="hello"} 556667219878 (518.44 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 670
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 127393.6 (35h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1541932
telemt_connections_bad_total 75784
telemt_handshake_timeouts_total 26801
telemt_upstream_connect_attempt_total 92051
telemt_upstream_connect_success_total 89600
telemt_upstream_connect_fail_total 2451
telemt_upstream_connect_attempts_per_request{bucket="1"} 92051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2451
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38917
telemt_me_reconnect_success_total 18495
telemt_me_reader_eof_total 20282
telemt_me_idle_close_by_peer_total 20279
telemt_me_route_drop_no_conn_total 620023
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1261498
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4907
telemt_desync_full_logged_total 1587
telemt_desync_suppressed_total 3320
telemt_desync_frames_bucket_total{bucket="1_2"} 1167
telemt_desync_frames_bucket_total{bucket="3_10"} 2038
telemt_desync_frames_bucket_total{bucket="gt_10"} 1702
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 19476
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18475
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 981
telemt_user_connections_total{user="hello"} 1324762
telemt_user_connections_current{user="hello"} 1907
telemt_user_octets_from_client{user="hello"} 21808194146 (20.31 GB)
telemt_user_octets_to_client{user="hello"} 648310364522 (603.79 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 127365.8 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1094873
telemt_connections_bad_total 105987
telemt_handshake_timeouts_total 10805
telemt_upstream_connect_attempt_total 48979
telemt_upstream_connect_success_total 48303
telemt_upstream_connect_fail_total 676
telemt_upstream_connect_attempts_per_request{bucket="1"} 48979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 676
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60456
telemt_me_reconnect_success_total 25486
telemt_me_reader_eof_total 27564
telemt_me_idle_close_by_peer_total 27561
telemt_me_route_drop_no_conn_total 352496
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901119
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3901
telemt_desync_full_logged_total 1203
telemt_desync_suppressed_total 2698
telemt_desync_frames_bucket_total{bucket="1_2"} 1106
telemt_desync_frames_bucket_total{bucket="3_10"} 1513
telemt_desync_frames_bucket_total{bucket="gt_10"} 1282
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26972
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25478
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1486
telemt_user_connections_total{user="hello"} 917570
telemt_user_connections_current{user="hello"} 1741
telemt_user_octets_from_client{user="hello"} 17313276252 (16.12 GB)
telemt_user_octets_to_client{user="hello"} 459204983148 (427.67 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 591
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 127527.0 (35h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1228945
telemt_connections_bad_total 128046
telemt_handshake_timeouts_total 10650
telemt_upstream_connect_attempt_total 25306
telemt_upstream_connect_success_total 25156
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 25306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 30127
telemt_me_reconnect_success_total 18830
telemt_me_reader_eof_total 20398
telemt_me_idle_close_by_peer_total 20396
telemt_me_route_drop_no_conn_total 832597
telemt_me_route_drop_channel_closed_total 91
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1206196
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2296
telemt_desync_full_logged_total 808
telemt_desync_suppressed_total 1488
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 877
telemt_desync_frames_bucket_total{bucket="gt_10"} 909
telemt_pool_swap_total 116
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19472
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18816
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 642
telemt_user_connections_total{user="hello"} 1014867
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 16109616296 (15.00 GB)
telemt_user_octets_to_client{user="hello"} 449544046832 (418.67 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 75293.6 (20h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600705
telemt_connections_bad_total 57409
telemt_handshake_timeouts_total 13665
telemt_upstream_connect_attempt_total 25913
telemt_upstream_connect_success_total 25643
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 25913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 33371
telemt_me_reconnect_success_total 21754
telemt_me_reader_eof_total 22991
telemt_me_idle_close_by_peer_total 22991
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 148979
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440881
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1947
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1297
telemt_desync_frames_bucket_total{bucket="1_2"} 326
telemt_desync_frames_bucket_total{bucket="3_10"} 863
telemt_desync_frames_bucket_total{bucket="gt_10"} 758
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22351
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21709
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 440639
telemt_user_connections_current{user="hello"} 1174
telemt_user_octets_from_client{user="hello"} 26923184093 (25.07 GB)
telemt_user_octets_to_client{user="hello"} 341696914302 (318.23 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 152
```