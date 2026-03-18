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

# Server Metrics 2026-03-18 06:01:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 127001.2 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1530071
telemt_connections_bad_total 10683
telemt_handshake_timeouts_total 35827
telemt_upstream_connect_attempt_total 27575
telemt_upstream_connect_success_total 27056
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 27575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12989
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 35598
telemt_me_reconnect_success_total 18447
telemt_me_reader_eof_total 20004
telemt_me_idle_close_by_peer_total 20003
telemt_me_route_drop_no_conn_total 620106
telemt_me_route_drop_channel_closed_total 169
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1348947
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8232
telemt_desync_full_logged_total 2480
telemt_desync_suppressed_total 5752
telemt_desync_frames_bucket_total{bucket="1_2"} 2159
telemt_desync_frames_bucket_total{bucket="3_10"} 3167
telemt_desync_frames_bucket_total{bucket="gt_10"} 2906
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 19260
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18425
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 813
telemt_user_connections_total{user="hello"} 1343169
telemt_user_connections_current{user="hello"} 973
telemt_user_octets_from_client{user="hello"} 32127594207 (29.92 GB)
telemt_user_octets_to_client{user="hello"} 483384023919 (450.19 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 389
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 127253.7 (35h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1642066
telemt_connections_bad_total 78617
telemt_handshake_timeouts_total 53315
telemt_upstream_connect_attempt_total 471108
telemt_upstream_connect_success_total 469472
telemt_upstream_connect_fail_total 1636
telemt_upstream_connect_attempts_per_request{bucket="1"} 471108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1636
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126945
telemt_me_reconnect_success_total 20213
telemt_me_reader_eof_total 22519
telemt_me_idle_close_by_peer_total 22506
telemt_me_route_drop_no_conn_total 434133
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989593
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4520
telemt_desync_full_logged_total 1563
telemt_desync_suppressed_total 2957
telemt_desync_frames_bucket_total{bucket="1_2"} 883
telemt_desync_frames_bucket_total{bucket="3_10"} 1816
telemt_desync_frames_bucket_total{bucket="gt_10"} 1821
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 21844
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20195
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1631
telemt_user_connections_total{user="hello"} 1431936
telemt_user_connections_current{user="hello"} 1923
telemt_user_octets_from_client{user="hello"} 19935755157 (18.57 GB)
telemt_user_octets_to_client{user="hello"} 551477352106 (513.60 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 127029.2 (35h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127525
telemt_connections_bad_total 75219
telemt_handshake_timeouts_total 30330
telemt_upstream_connect_attempt_total 28938
telemt_upstream_connect_success_total 28774
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 28938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15451
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 43096
telemt_me_reconnect_success_total 22392
telemt_me_reader_eof_total 24331
telemt_me_idle_close_by_peer_total 24324
telemt_me_route_drop_no_conn_total 391071
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 871011
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2989
telemt_desync_full_logged_total 970
telemt_desync_suppressed_total 2019
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 1168
telemt_desync_frames_bucket_total{bucket="gt_10"} 1018
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 23340
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22380
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 948
telemt_user_connections_total{user="hello"} 869106
telemt_user_connections_current{user="hello"} 1397
telemt_user_octets_from_client{user="hello"} 46660373548 (43.46 GB)
telemt_user_octets_to_client{user="hello"} 422445625968 (393.43 GB)
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 127088.8 (35h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1529999
telemt_connections_bad_total 75405
telemt_handshake_timeouts_total 26652
telemt_upstream_connect_attempt_total 92021
telemt_upstream_connect_success_total 89570
telemt_upstream_connect_fail_total 2451
telemt_upstream_connect_attempts_per_request{bucket="1"} 92021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2451
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38887
telemt_me_reconnect_success_total 18465
telemt_me_reader_eof_total 20251
telemt_me_idle_close_by_peer_total 20248
telemt_me_route_drop_no_conn_total 613949
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1250770
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4875
telemt_desync_full_logged_total 1578
telemt_desync_suppressed_total 3297
telemt_desync_frames_bucket_total{bucket="1_2"} 1159
telemt_desync_frames_bucket_total{bucket="3_10"} 2031
telemt_desync_frames_bucket_total{bucket="gt_10"} 1685
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 19446
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18445
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 981
telemt_user_connections_total{user="hello"} 1314043
telemt_user_connections_current{user="hello"} 1910
telemt_user_octets_from_client{user="hello"} 21644088702 (20.16 GB)
telemt_user_octets_to_client{user="hello"} 643960743466 (599.74 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 542
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 127060.5 (35h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1084648
telemt_connections_bad_total 105931
telemt_handshake_timeouts_total 10696
telemt_upstream_connect_attempt_total 48931
telemt_upstream_connect_success_total 48255
telemt_upstream_connect_fail_total 676
telemt_upstream_connect_attempts_per_request{bucket="1"} 48931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 676
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60408
telemt_me_reconnect_success_total 25439
telemt_me_reader_eof_total 27514
telemt_me_idle_close_by_peer_total 27511
telemt_me_route_drop_no_conn_total 348636
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 891714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3870
telemt_desync_full_logged_total 1193
telemt_desync_suppressed_total 2677
telemt_desync_frames_bucket_total{bucket="1_2"} 1104
telemt_desync_frames_bucket_total{bucket="3_10"} 1504
telemt_desync_frames_bucket_total{bucket="gt_10"} 1262
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26925
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25431
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1486
telemt_user_connections_total{user="hello"} 908170
telemt_user_connections_current{user="hello"} 1612
telemt_user_octets_from_client{user="hello"} 17192747056 (16.01 GB)
telemt_user_octets_to_client{user="hello"} 454644181576 (423.42 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 546
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 127221.8 (35h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1224966
telemt_connections_bad_total 127947
telemt_handshake_timeouts_total 10636
telemt_upstream_connect_attempt_total 25275
telemt_upstream_connect_success_total 25125
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 25275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12924
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 30096
telemt_me_reconnect_success_total 18800
telemt_me_reader_eof_total 20367
telemt_me_idle_close_by_peer_total 20365
telemt_me_route_drop_no_conn_total 831008
telemt_me_route_drop_channel_closed_total 91
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1202442
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2282
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 1480
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 869
telemt_desync_frames_bucket_total{bucket="gt_10"} 903
telemt_pool_swap_total 116
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19441
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18786
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 641
telemt_user_connections_total{user="hello"} 1011122
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 16063543444 (14.96 GB)
telemt_user_octets_to_client{user="hello"} 448436875624 (417.64 GB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 74988.8 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592969
telemt_connections_bad_total 56657
telemt_handshake_timeouts_total 13614
telemt_upstream_connect_attempt_total 25894
telemt_upstream_connect_success_total 25624
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 25894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 33352
telemt_me_reconnect_success_total 21736
telemt_me_reader_eof_total 22970
telemt_me_idle_close_by_peer_total 22970
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 146580
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434442
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1912
telemt_desync_full_logged_total 638
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 745
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22330
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21691
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 434199
telemt_user_connections_current{user="hello"} 1204
telemt_user_octets_from_client{user="hello"} 26823926633 (24.98 GB)
telemt_user_octets_to_client{user="hello"} 337057137458 (313.91 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 162
```