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

# Server Metrics 2026-03-18 07:59:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 134029.6 (37h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1886671
telemt_connections_bad_total 11844
telemt_handshake_timeouts_total 38664
telemt_upstream_connect_attempt_total 29046
telemt_upstream_connect_success_total 28508
telemt_upstream_connect_fail_total 537
telemt_upstream_connect_attempts_per_request{bucket="1"} 29045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 537
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 36736
telemt_me_reconnect_success_total 19546
telemt_me_reader_eof_total 21151
telemt_me_idle_close_by_peer_total 21149
telemt_me_route_drop_no_conn_total 685326
telemt_me_route_drop_channel_closed_total 202
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1489092
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8910
telemt_desync_full_logged_total 2718
telemt_desync_suppressed_total 6192
telemt_desync_frames_bucket_total{bucket="1_2"} 2304
telemt_desync_frames_bucket_total{bucket="3_10"} 3438
telemt_desync_frames_bucket_total{bucket="gt_10"} 3168
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20402
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19524
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 856
telemt_user_connections_total{user="hello"} 1483335
telemt_user_connections_current{user="hello"} 1220
telemt_user_octets_from_client{user="hello"} 34204752127 (31.86 GB)
telemt_user_octets_to_client{user="hello"} 522126936083 (486.27 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 134281.3 (37h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1991444
telemt_connections_bad_total 103787
telemt_handshake_timeouts_total 62053
telemt_upstream_connect_attempt_total 472530
telemt_upstream_connect_success_total 470876
telemt_upstream_connect_fail_total 1654
telemt_upstream_connect_attempts_per_request{bucket="1"} 472530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1654
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 412
telemt_me_reconnect_attempts_total 134162
telemt_me_reconnect_success_total 21250
telemt_me_reader_eof_total 23757
telemt_me_idle_close_by_peer_total 23744
telemt_me_route_drop_no_conn_total 603496
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1291870
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5912
telemt_desync_full_logged_total 2051
telemt_desync_suppressed_total 3861
telemt_desync_frames_bucket_total{bucket="1_2"} 1111
telemt_desync_frames_bucket_total{bucket="3_10"} 2395
telemt_desync_frames_bucket_total{bucket="gt_10"} 2406
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 23083
telemt_me_refill_failed_total 3522
telemt_me_writer_restored_same_endpoint_total 21232
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1833
telemt_user_connections_total{user="hello"} 1734278
telemt_user_connections_current{user="hello"} 2956
telemt_user_octets_from_client{user="hello"} 29226268745 (27.22 GB)
telemt_user_octets_to_client{user="hello"} 683001291038 (636.09 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 911
telemt_user_unique_ips_recent_window{user="hello"} 436
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 134056.8 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1496111
telemt_connections_bad_total 91528
telemt_handshake_timeouts_total 35069
telemt_upstream_connect_attempt_total 30260
telemt_upstream_connect_success_total 30092
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 30260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 44100
telemt_me_reconnect_success_total 23374
telemt_me_reader_eof_total 25370
telemt_me_idle_close_by_peer_total 25362
telemt_me_route_drop_no_conn_total 563066
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1091083
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3941
telemt_desync_full_logged_total 1326
telemt_desync_suppressed_total 2615
telemt_desync_frames_bucket_total{bucket="1_2"} 1072
telemt_desync_frames_bucket_total{bucket="3_10"} 1519
telemt_desync_frames_bucket_total{bucket="gt_10"} 1350
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24355
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 23362
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 981
telemt_user_connections_total{user="hello"} 1089079
telemt_user_connections_current{user="hello"} 1862
telemt_user_octets_from_client{user="hello"} 50344235844 (46.89 GB)
telemt_user_octets_to_client{user="hello"} 516811350684 (481.32 GB)
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 134116.3 (37h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1931801
telemt_connections_bad_total 88451
telemt_handshake_timeouts_total 36012
telemt_upstream_connect_attempt_total 93308
telemt_upstream_connect_success_total 90847
telemt_upstream_connect_fail_total 2461
telemt_upstream_connect_attempts_per_request{bucket="1"} 93308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15731
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 388
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2461
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 40946
telemt_me_reconnect_success_total 19414
telemt_me_reader_eof_total 21273
telemt_me_idle_close_by_peer_total 21270
telemt_me_route_drop_no_conn_total 957681
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1608111
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6333
telemt_desync_full_logged_total 1942
telemt_desync_suppressed_total 4391
telemt_desync_frames_bucket_total{bucket="1_2"} 1440
telemt_desync_frames_bucket_total{bucket="3_10"} 2598
telemt_desync_frames_bucket_total{bucket="gt_10"} 2295
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20452
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19394
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1038
telemt_user_connections_total{user="hello"} 1671196
telemt_user_connections_current{user="hello"} 2625
telemt_user_octets_from_client{user="hello"} 26886492854 (25.04 GB)
telemt_user_octets_to_client{user="hello"} 736034638866 (685.49 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 720
telemt_user_unique_ips_recent_window{user="hello"} 332
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 134088.1 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1387161
telemt_connections_bad_total 121107
telemt_handshake_timeouts_total 15813
telemt_upstream_connect_attempt_total 50030
telemt_upstream_connect_success_total 49335
telemt_upstream_connect_fail_total 695
telemt_upstream_connect_attempts_per_request{bucket="1"} 50030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 695
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 67707
telemt_me_reconnect_success_total 26203
telemt_me_reader_eof_total 28491
telemt_me_idle_close_by_peer_total 28488
telemt_me_route_drop_no_conn_total 525009
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1148406
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5012
telemt_desync_full_logged_total 1548
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 1284
telemt_desync_frames_bucket_total{bucket="3_10"} 1951
telemt_desync_frames_bucket_total{bucket="gt_10"} 1777
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27905
telemt_me_refill_failed_total 1291
telemt_me_writer_restored_same_endpoint_total 26195
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1702
telemt_user_connections_total{user="hello"} 1164690
telemt_user_connections_current{user="hello"} 2420
telemt_user_octets_from_client{user="hello"} 22622503312 (21.07 GB)
telemt_user_octets_to_client{user="hello"} 572762835612 (533.43 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 739
telemt_user_unique_ips_recent_window{user="hello"} 363
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 134249.9 (37h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1330761
telemt_connections_bad_total 136645
telemt_handshake_timeouts_total 11119
telemt_upstream_connect_attempt_total 26769
telemt_upstream_connect_success_total 26611
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 26769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13641
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 31227
telemt_me_reconnect_success_total 19917
telemt_me_reader_eof_total 21539
telemt_me_idle_close_by_peer_total 21536
telemt_me_route_drop_no_conn_total 884801
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1293955
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2567
telemt_desync_full_logged_total 901
telemt_desync_suppressed_total 1666
telemt_desync_frames_bucket_total{bucket="1_2"} 553
telemt_desync_frames_bucket_total{bucket="3_10"} 994
telemt_desync_frames_bucket_total{bucket="gt_10"} 1020
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20577
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19903
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 1102610
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 16949504296 (15.79 GB)
telemt_user_octets_to_client{user="hello"} 475304369428 (442.66 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 82016.4 (22h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 799257
telemt_connections_bad_total 77416
telemt_handshake_timeouts_total 17145
telemt_upstream_connect_attempt_total 27337
telemt_upstream_connect_success_total 27039
telemt_upstream_connect_fail_total 297
telemt_upstream_connect_attempts_per_request{bucket="1"} 27336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 297
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 35624
telemt_me_reconnect_success_total 22813
telemt_me_reader_eof_total 24109
telemt_me_idle_close_by_peer_total 24109
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 239183
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602757
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2448
telemt_desync_full_logged_total 839
telemt_desync_suppressed_total 1609
telemt_desync_frames_bucket_total{bucket="1_2"} 422
telemt_desync_frames_bucket_total{bucket="3_10"} 1010
telemt_desync_frames_bucket_total{bucket="gt_10"} 1016
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23464
telemt_me_refill_failed_total 396
telemt_me_writer_restored_same_endpoint_total 22766
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 651
telemt_user_connections_total{user="hello"} 602419
telemt_user_connections_current{user="hello"} 1760
telemt_user_octets_from_client{user="hello"} 29933086961 (27.88 GB)
telemt_user_octets_to_client{user="hello"} 430111483686 (400.57 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 240
```