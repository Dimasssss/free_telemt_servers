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

# Server Metrics 2026-03-18 05:46:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 126085.3 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1499546
telemt_connections_bad_total 10600
telemt_handshake_timeouts_total 35536
telemt_upstream_connect_attempt_total 27434
telemt_upstream_connect_success_total 26915
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 27434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 35491
telemt_me_reconnect_success_total 18341
telemt_me_reader_eof_total 19889
telemt_me_idle_close_by_peer_total 19888
telemt_me_route_drop_no_conn_total 614772
telemt_me_route_drop_channel_closed_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1335486
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8163
telemt_desync_full_logged_total 2454
telemt_desync_suppressed_total 5709
telemt_desync_frames_bucket_total{bucket="1_2"} 2137
telemt_desync_frames_bucket_total{bucket="3_10"} 3141
telemt_desync_frames_bucket_total{bucket="gt_10"} 2885
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 19151
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18319
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 810
telemt_user_connections_total{user="hello"} 1329713
telemt_user_connections_current{user="hello"} 885
telemt_user_octets_from_client{user="hello"} 31947479779 (29.75 GB)
telemt_user_octets_to_client{user="hello"} 476541201487 (443.81 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 126336.8 (35h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1611455
telemt_connections_bad_total 76420
telemt_handshake_timeouts_total 52782
telemt_upstream_connect_attempt_total 470930
telemt_upstream_connect_success_total 469296
telemt_upstream_connect_fail_total 1634
telemt_upstream_connect_attempts_per_request{bucket="1"} 470930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34784
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1634
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126812
telemt_me_reconnect_success_total 20082
telemt_me_reader_eof_total 22375
telemt_me_idle_close_by_peer_total 22362
telemt_me_route_drop_no_conn_total 423787
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 962574
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4350
telemt_desync_full_logged_total 1512
telemt_desync_suppressed_total 2838
telemt_desync_frames_bucket_total{bucket="1_2"} 857
telemt_desync_frames_bucket_total{bucket="3_10"} 1758
telemt_desync_frames_bucket_total{bucket="gt_10"} 1735
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 21710
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20064
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1628
telemt_user_connections_total{user="hello"} 1404929
telemt_user_connections_current{user="hello"} 1587
telemt_user_octets_from_client{user="hello"} 19483043025 (18.14 GB)
telemt_user_octets_to_client{user="hello"} 538174557598 (501.21 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 573
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 126113.0 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091042
telemt_connections_bad_total 74126
telemt_handshake_timeouts_total 29304
telemt_upstream_connect_attempt_total 28797
telemt_upstream_connect_success_total 28633
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 28797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42999
telemt_me_reconnect_success_total 22296
telemt_me_reader_eof_total 24232
telemt_me_idle_close_by_peer_total 24225
telemt_me_route_drop_no_conn_total 383444
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851192
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2868
telemt_desync_full_logged_total 941
telemt_desync_suppressed_total 1927
telemt_desync_frames_bucket_total{bucket="1_2"} 786
telemt_desync_frames_bucket_total{bucket="3_10"} 1115
telemt_desync_frames_bucket_total{bucket="gt_10"} 967
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 23242
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22284
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 946
telemt_user_connections_total{user="hello"} 849291
telemt_user_connections_current{user="hello"} 1302
telemt_user_octets_from_client{user="hello"} 46316014736 (43.14 GB)
telemt_user_octets_to_client{user="hello"} 412150742020 (383.85 GB)
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 126172.3 (35h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1501610
telemt_connections_bad_total 74067
telemt_handshake_timeouts_total 26126
telemt_upstream_connect_attempt_total 91834
telemt_upstream_connect_success_total 89385
telemt_upstream_connect_fail_total 2449
telemt_upstream_connect_attempts_per_request{bucket="1"} 91834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15083
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2449
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38744
telemt_me_reconnect_success_total 18326
telemt_me_reader_eof_total 20102
telemt_me_idle_close_by_peer_total 20099
telemt_me_route_drop_no_conn_total 603162
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1225963
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4756
telemt_desync_full_logged_total 1546
telemt_desync_suppressed_total 3210
telemt_desync_frames_bucket_total{bucket="1_2"} 1126
telemt_desync_frames_bucket_total{bucket="3_10"} 1992
telemt_desync_frames_bucket_total{bucket="gt_10"} 1638
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 19305
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18306
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 979
telemt_user_connections_total{user="hello"} 1289236
telemt_user_connections_current{user="hello"} 1698
telemt_user_octets_from_client{user="hello"} 21054331022 (19.61 GB)
telemt_user_octets_to_client{user="hello"} 631636517970 (588.26 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 506
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 126144.0 (35h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1058501
telemt_connections_bad_total 105687
telemt_handshake_timeouts_total 10315
telemt_upstream_connect_attempt_total 48800
telemt_upstream_connect_success_total 48126
telemt_upstream_connect_fail_total 674
telemt_upstream_connect_attempts_per_request{bucket="1"} 48800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 674
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60324
telemt_me_reconnect_success_total 25356
telemt_me_reader_eof_total 27426
telemt_me_idle_close_by_peer_total 27423
telemt_me_route_drop_no_conn_total 340470
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 868088
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3767
telemt_desync_full_logged_total 1159
telemt_desync_suppressed_total 2608
telemt_desync_frames_bucket_total{bucket="1_2"} 1093
telemt_desync_frames_bucket_total{bucket="3_10"} 1461
telemt_desync_frames_bucket_total{bucket="gt_10"} 1213
telemt_pool_swap_total 68
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26839
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25348
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1483
telemt_user_connections_total{user="hello"} 884552
telemt_user_connections_current{user="hello"} 1430
telemt_user_octets_from_client{user="hello"} 16792251920 (15.64 GB)
telemt_user_octets_to_client{user="hello"} 444050207968 (413.55 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 126305.0 (35h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1214009
telemt_connections_bad_total 127754
telemt_handshake_timeouts_total 10565
telemt_upstream_connect_attempt_total 25129
telemt_upstream_connect_success_total 24982
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 25129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29996
telemt_me_reconnect_success_total 18700
telemt_me_reader_eof_total 20261
telemt_me_idle_close_by_peer_total 20259
telemt_me_route_drop_no_conn_total 826997
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1192299
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2270
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 1475
telemt_desync_frames_bucket_total{bucket="1_2"} 507
telemt_desync_frames_bucket_total{bucket="3_10"} 863
telemt_desync_frames_bucket_total{bucket="gt_10"} 900
telemt_pool_swap_total 115
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19339
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18686
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 639
telemt_user_connections_total{user="hello"} 1000980
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 15896710604 (14.80 GB)
telemt_user_octets_to_client{user="hello"} 445710043256 (415.10 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 74072.2 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 574245
telemt_connections_bad_total 55289
telemt_handshake_timeouts_total 13546
telemt_upstream_connect_attempt_total 25739
telemt_upstream_connect_success_total 25472
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 25739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 33243
telemt_me_reconnect_success_total 21628
telemt_me_reader_eof_total 22855
telemt_me_idle_close_by_peer_total 22855
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 141561
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418603
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1826
telemt_desync_full_logged_total 611
telemt_desync_suppressed_total 1215
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 814
telemt_desync_frames_bucket_total{bucket="gt_10"} 709
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22219
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21584
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 591
telemt_user_connections_total{user="hello"} 418357
telemt_user_connections_current{user="hello"} 1000
telemt_user_octets_from_client{user="hello"} 26525869021 (24.70 GB)
telemt_user_octets_to_client{user="hello"} 328336039330 (305.79 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 118
```