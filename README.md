# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 05:08:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 42638.0 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 807321
telemt_connections_bad_total 53870
telemt_connections_current 1273
telemt_connections_me_current 1273
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18487
telemt_upstream_connect_attempt_total 8425
telemt_upstream_connect_success_total 8327
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 8425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5125
telemt_me_reconnect_success_total 5082
telemt_me_reader_eof_total 5383
telemt_me_idle_close_by_peer_total 5382
telemt_me_route_drop_no_conn_total 225333
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 647878
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3453
telemt_desync_full_logged_total 1239
telemt_desync_suppressed_total 2214
telemt_desync_frames_bucket_total{bucket="1_2"} 666
telemt_desync_frames_bucket_total{bucket="3_10"} 1347
telemt_desync_frames_bucket_total{bucket="gt_10"} 1440
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 5131
telemt_me_writer_restored_same_endpoint_total 5069
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 649390
telemt_user_connections_current{user="hello"} 1273
telemt_user_octets_from_client{user="hello"} 32451075816 (30.22 GB)
telemt_user_octets_to_client{user="hello"} 221475120349 (206.26 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 59093.8 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3659899
telemt_connections_bad_total 324338
telemt_connections_current 3311
telemt_connections_me_current 3311
telemt_handshake_timeouts_total 82211
telemt_upstream_connect_attempt_total 11221
telemt_upstream_connect_success_total 11015
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 11221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11108
telemt_me_reconnect_success_total 6857
telemt_me_reader_eof_total 7334
telemt_me_idle_close_by_peer_total 7334
telemt_me_route_drop_no_conn_total 1649384
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2999172
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12418
telemt_desync_full_logged_total 4156
telemt_desync_suppressed_total 8262
telemt_desync_frames_bucket_total{bucket="1_2"} 2371
telemt_desync_frames_bucket_total{bucket="3_10"} 4814
telemt_desync_frames_bucket_total{bucket="gt_10"} 5233
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 57
telemt_me_writer_removed_unexpected_total 7073
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6802
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 2998901
telemt_user_connections_current{user="hello"} 3311
telemt_user_octets_from_client{user="hello"} 45496035446 (42.37 GB)
telemt_user_octets_to_client{user="hello"} 1137946692054 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1258
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 59071.8 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3322643
telemt_connections_bad_total 491553
telemt_connections_current 2839
telemt_connections_me_current 2839
telemt_handshake_timeouts_total 52034
telemt_upstream_connect_attempt_total 9587
telemt_upstream_connect_success_total 9522
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7533
telemt_me_reconnect_success_total 6592
telemt_me_reader_eof_total 6943
telemt_me_idle_close_by_peer_total 6942
telemt_me_route_drop_no_conn_total 2033301
telemt_me_route_drop_channel_closed_total 183
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2335055
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8646
telemt_desync_full_logged_total 2668
telemt_desync_suppressed_total 5978
telemt_desync_frames_bucket_total{bucket="1_2"} 2153
telemt_desync_frames_bucket_total{bucket="3_10"} 3289
telemt_desync_frames_bucket_total{bucket="gt_10"} 3204
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 75
telemt_me_writer_removed_unexpected_total 6663
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6591
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 2330110
telemt_user_connections_current{user="hello"} 2839
telemt_user_octets_from_client{user="hello"} 35326039868 (32.90 GB)
telemt_user_octets_to_client{user="hello"} 944320817940 (879.47 GB)
telemt_user_unique_ips_current{user="hello"} 1013
telemt_user_unique_ips_recent_window{user="hello"} 339
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 59059.7 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3022880
telemt_connections_bad_total 226067
telemt_connections_current 2906
telemt_connections_me_current 2906
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 40033
telemt_upstream_connect_attempt_total 63563
telemt_upstream_connect_success_total 59002
telemt_upstream_connect_fail_total 4561
telemt_upstream_connect_attempts_per_request{bucket="1"} 63563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4561
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9865
telemt_me_reconnect_success_total 6930
telemt_me_reader_eof_total 7236
telemt_me_idle_close_by_peer_total 7235
telemt_me_route_drop_no_conn_total 2060306
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2457252
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9382
telemt_desync_full_logged_total 2989
telemt_desync_suppressed_total 6393
telemt_desync_frames_bucket_total{bucket="1_2"} 2251
telemt_desync_frames_bucket_total{bucket="3_10"} 3454
telemt_desync_frames_bucket_total{bucket="gt_10"} 3677
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 541
telemt_me_writer_removed_unexpected_total 7615
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6926
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 685
telemt_user_connections_total{user="hello"} 2504433
telemt_user_connections_current{user="hello"} 2906
telemt_user_octets_from_client{user="hello"} 39189536909 (36.50 GB)
telemt_user_octets_to_client{user="hello"} 750796431583 (699.23 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 980
telemt_user_unique_ips_recent_window{user="hello"} 398
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 112782.8 (31h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6773032
telemt_connections_bad_total 1187615
telemt_connections_current 3063
telemt_connections_me_current 3063
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 120376
telemt_upstream_connect_attempt_total 129588
telemt_upstream_connect_success_total 96286
telemt_upstream_connect_fail_total 33302
telemt_upstream_connect_attempts_per_request{bucket="1"} 129588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33302
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80028
telemt_me_reconnect_success_total 14348
telemt_me_reader_eof_total 15438
telemt_me_idle_close_by_peer_total 15424
telemt_me_route_drop_no_conn_total 2914533
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4777986
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20768
telemt_desync_full_logged_total 6602
telemt_desync_suppressed_total 14166
telemt_desync_frames_bucket_total{bucket="1_2"} 3689
telemt_desync_frames_bucket_total{bucket="3_10"} 8589
telemt_desync_frames_bucket_total{bucket="gt_10"} 8490
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 14675
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14323
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 4853046
telemt_user_connections_current{user="hello"} 3063
telemt_user_octets_from_client{user="hello"} 76796797836 (71.52 GB)
telemt_user_octets_to_client{user="hello"} 1915390275008 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1066
telemt_user_unique_ips_recent_window{user="hello"} 410
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 59022.6 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1488399
telemt_connections_bad_total 103043
telemt_connections_current 802
telemt_connections_me_current 802
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14206
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473475
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1539
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1311416
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 8954975115 (8.34 GB)
telemt_user_octets_to_client{user="hello"} 146621936702 (136.55 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 59024.2 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2385134
telemt_connections_bad_total 153681
telemt_connections_current 2887
telemt_connections_me_current 2887
telemt_handshake_timeouts_total 43984
telemt_upstream_connect_attempt_total 10606
telemt_upstream_connect_success_total 10540
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7651
telemt_me_reconnect_success_total 7602
telemt_me_reader_eof_total 8034
telemt_me_idle_close_by_peer_total 8034
telemt_me_route_drop_no_conn_total 841791
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2003210
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10198
telemt_desync_full_logged_total 3296
telemt_desync_suppressed_total 6902
telemt_desync_frames_bucket_total{bucket="1_2"} 1993
telemt_desync_frames_bucket_total{bucket="3_10"} 3586
telemt_desync_frames_bucket_total{bucket="gt_10"} 4619
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7708
telemt_me_writer_restored_same_endpoint_total 7585
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 2001908
telemt_user_connections_current{user="hello"} 2887
telemt_user_octets_from_client{user="hello"} 42493115624 (39.57 GB)
telemt_user_octets_to_client{user="hello"} 1057243044520 (984.63 GB)
telemt_user_unique_ips_current{user="hello"} 954
telemt_user_unique_ips_recent_window{user="hello"} 334
```