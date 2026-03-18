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

# Server Metrics 2026-03-18 00:46:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 108063.1 (30h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1267422
telemt_connections_bad_total 9593
telemt_handshake_timeouts_total 32457
telemt_upstream_connect_attempt_total 24173
telemt_upstream_connect_success_total 23673
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 24172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33127
telemt_me_reconnect_success_total 15990
telemt_me_reader_eof_total 17359
telemt_me_idle_close_by_peer_total 17358
telemt_me_route_drop_no_conn_total 557798
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1165140
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7532
telemt_desync_full_logged_total 2206
telemt_desync_suppressed_total 5326
telemt_desync_frames_bucket_total{bucket="1_2"} 2015
telemt_desync_frames_bucket_total{bucket="3_10"} 2854
telemt_desync_frames_bucket_total{bucket="gt_10"} 2663
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16762
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15968
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 772
telemt_user_connections_total{user="hello"} 1159352
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 22750741335 (21.19 GB)
telemt_user_octets_to_client{user="hello"} 416089341307 (387.51 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 108314.4 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1345566
telemt_connections_bad_total 62104
telemt_handshake_timeouts_total 46127
telemt_upstream_connect_attempt_total 466739
telemt_upstream_connect_success_total 465193
telemt_upstream_connect_fail_total 1546
telemt_upstream_connect_attempts_per_request{bucket="1"} 466739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1546
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122288
telemt_me_reconnect_success_total 16859
telemt_me_reader_eof_total 18975
telemt_me_idle_close_by_peer_total 18965
telemt_me_route_drop_no_conn_total 347880
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726542
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3309
telemt_desync_full_logged_total 1106
telemt_desync_suppressed_total 2203
telemt_desync_frames_bucket_total{bucket="1_2"} 644
telemt_desync_frames_bucket_total{bucket="3_10"} 1364
telemt_desync_frames_bucket_total{bucket="gt_10"} 1301
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 18404
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16841
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1545
telemt_user_connections_total{user="hello"} 1168891
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 15866165565 (14.78 GB)
telemt_user_octets_to_client{user="hello"} 399905153094 (372.44 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 108090.5 (30h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796992
telemt_connections_bad_total 52182
telemt_handshake_timeouts_total 24084
telemt_upstream_connect_attempt_total 25397
telemt_upstream_connect_success_total 25252
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 25397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13586
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40478
telemt_me_reconnect_success_total 19794
telemt_me_reader_eof_total 21558
telemt_me_idle_close_by_peer_total 21551
telemt_me_route_drop_no_conn_total 321725
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 677135
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2164
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 715
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 20709
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19782
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 915
telemt_user_connections_total{user="hello"} 675286
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 34141358348 (31.80 GB)
telemt_user_octets_to_client{user="hello"} 298560008668 (278.06 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 108149.8 (30h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1283512
telemt_connections_bad_total 53382
telemt_handshake_timeouts_total 21839
telemt_upstream_connect_attempt_total 86519
telemt_upstream_connect_success_total 85097
telemt_upstream_connect_fail_total 1422
telemt_upstream_connect_attempts_per_request{bucket="1"} 86519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1422
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36032
telemt_me_reconnect_success_total 15671
telemt_me_reader_eof_total 17293
telemt_me_idle_close_by_peer_total 17291
telemt_me_route_drop_no_conn_total 525069
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1044755
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3939
telemt_desync_full_logged_total 1304
telemt_desync_suppressed_total 2635
telemt_desync_frames_bucket_total{bucket="1_2"} 964
telemt_desync_frames_bucket_total{bucket="3_10"} 1657
telemt_desync_frames_bucket_total{bucket="gt_10"} 1318
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 16600
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15661
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 929
telemt_user_connections_total{user="hello"} 1107875
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 17395010451 (16.20 GB)
telemt_user_octets_to_client{user="hello"} 519063823310 (483.42 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 108121.8 (30h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 841730
telemt_connections_bad_total 99269
telemt_handshake_timeouts_total 6768
telemt_upstream_connect_attempt_total 44608
telemt_upstream_connect_success_total 43994
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 44608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57054
telemt_me_reconnect_success_total 22096
telemt_me_reader_eof_total 23992
telemt_me_idle_close_by_peer_total 23990
telemt_me_route_drop_no_conn_total 266703
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 677324
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3180
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23545
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22088
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1449
telemt_user_connections_total{user="hello"} 693932
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 13586440016 (12.65 GB)
telemt_user_octets_to_client{user="hello"} 348015321932 (324.11 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 108282.7 (30h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082823
telemt_connections_bad_total 105272
telemt_handshake_timeouts_total 9651
telemt_upstream_connect_attempt_total 21547
telemt_upstream_connect_success_total 21428
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 21547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27302
telemt_me_reconnect_success_total 16019
telemt_me_reader_eof_total 17389
telemt_me_idle_close_by_peer_total 17387
telemt_me_route_drop_no_conn_total 730217
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1048793
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 95
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16629
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16005
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 898233
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 14510509232 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 381625601676 (355.42 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 56050.0 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395435
telemt_connections_bad_total 44684
telemt_handshake_timeouts_total 10863
telemt_upstream_connect_attempt_total 21061
telemt_upstream_connect_success_total 20866
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 21060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29497
telemt_me_reconnect_success_total 17897
telemt_me_reader_eof_total 18925
telemt_me_idle_close_by_peer_total 18925
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 99100
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291485
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1110
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 761
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18462
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17866
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 565
telemt_user_connections_total{user="hello"} 291425
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 22234972221 (20.71 GB)
telemt_user_octets_to_client{user="hello"} 242548086154 (225.89 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 27
```