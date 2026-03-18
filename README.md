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

# Server Metrics 2026-03-18 01:11:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 109591.5 (30h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280605
telemt_connections_bad_total 9601
telemt_handshake_timeouts_total 32496
telemt_upstream_connect_attempt_total 24487
telemt_upstream_connect_success_total 23988
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 24487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33379
telemt_me_reconnect_success_total 16242
telemt_me_reader_eof_total 17636
telemt_me_idle_close_by_peer_total 17635
telemt_me_route_drop_no_conn_total 560939
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1178022
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7573
telemt_desync_full_logged_total 2224
telemt_desync_suppressed_total 5349
telemt_desync_frames_bucket_total{bucket="1_2"} 2025
telemt_desync_frames_bucket_total{bucket="3_10"} 2873
telemt_desync_frames_bucket_total{bucket="gt_10"} 2675
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 17018
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16220
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 776
telemt_user_connections_total{user="hello"} 1172235
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 22835281339 (21.27 GB)
telemt_user_octets_to_client{user="hello"} 418339327239 (389.61 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 109842.9 (30h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1357420
telemt_connections_bad_total 63397
telemt_handshake_timeouts_total 46421
telemt_upstream_connect_attempt_total 467057
telemt_upstream_connect_success_total 465506
telemt_upstream_connect_fail_total 1551
telemt_upstream_connect_attempts_per_request{bucket="1"} 467057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1551
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122553
telemt_me_reconnect_success_total 17123
telemt_me_reader_eof_total 19252
telemt_me_idle_close_by_peer_total 19242
telemt_me_route_drop_no_conn_total 349992
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 736327
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3424
telemt_desync_full_logged_total 1143
telemt_desync_suppressed_total 2281
telemt_desync_frames_bucket_total{bucket="1_2"} 670
telemt_desync_frames_bucket_total{bucket="3_10"} 1411
telemt_desync_frames_bucket_total{bucket="gt_10"} 1343
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 18671
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17105
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1548
telemt_user_connections_total{user="hello"} 1178677
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 15979118641 (14.88 GB)
telemt_user_octets_to_client{user="hello"} 404890896214 (377.08 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 109618.9 (30h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806687
telemt_connections_bad_total 53859
telemt_handshake_timeouts_total 24217
telemt_upstream_connect_attempt_total 25691
telemt_upstream_connect_success_total 25545
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 25691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40728
telemt_me_reconnect_success_total 20042
telemt_me_reader_eof_total 21826
telemt_me_idle_close_by_peer_total 21819
telemt_me_route_drop_no_conn_total 324091
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 684580
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2188
telemt_desync_full_logged_total 710
telemt_desync_suppressed_total 1478
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 846
telemt_desync_frames_bucket_total{bucket="gt_10"} 721
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 20961
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20030
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 919
telemt_user_connections_total{user="hello"} 682700
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 37709324404 (35.12 GB)
telemt_user_octets_to_client{user="hello"} 301858327420 (281.13 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 109678.5 (30h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1290408
telemt_connections_bad_total 54837
telemt_handshake_timeouts_total 21916
telemt_upstream_connect_attempt_total 86792
telemt_upstream_connect_success_total 85369
telemt_upstream_connect_fail_total 1423
telemt_upstream_connect_attempts_per_request{bucket="1"} 86792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1423
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36261
telemt_me_reconnect_success_total 15899
telemt_me_reader_eof_total 17535
telemt_me_idle_close_by_peer_total 17533
telemt_me_route_drop_no_conn_total 526991
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1049989
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3954
telemt_desync_full_logged_total 1307
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1660
telemt_desync_frames_bucket_total{bucket="gt_10"} 1328
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 16832
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15889
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 933
telemt_user_connections_total{user="hello"} 1113108
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 17470443327 (16.27 GB)
telemt_user_octets_to_client{user="hello"} 526696489378 (490.52 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 109650.3 (30h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 849180
telemt_connections_bad_total 99544
telemt_handshake_timeouts_total 6796
telemt_upstream_connect_attempt_total 45063
telemt_upstream_connect_success_total 44445
telemt_upstream_connect_fail_total 618
telemt_upstream_connect_attempts_per_request{bucket="1"} 45063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 618
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57460
telemt_me_reconnect_success_total 22501
telemt_me_reader_eof_total 24417
telemt_me_idle_close_by_peer_total 24415
telemt_me_route_drop_no_conn_total 269944
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 683990
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3181
telemt_desync_full_logged_total 945
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 903
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23952
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22493
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1451
telemt_user_connections_total{user="hello"} 700596
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 13632035176 (12.70 GB)
telemt_user_octets_to_client{user="hello"} 349783738140 (325.76 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 109811.3 (30h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1093912
telemt_connections_bad_total 109347
telemt_handshake_timeouts_total 9668
telemt_upstream_connect_attempt_total 21820
telemt_upstream_connect_success_total 21700
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 21820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27530
telemt_me_reconnect_success_total 16246
telemt_me_reader_eof_total 17630
telemt_me_idle_close_by_peer_total 17628
telemt_me_route_drop_no_conn_total 740715
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1061216
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
telemt_pool_swap_total 96
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16859
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16232
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 904744
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 14702084428 (13.69 GB)
telemt_user_octets_to_client{user="hello"} 387662133680 (361.04 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 57578.5 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402827
telemt_connections_bad_total 44691
telemt_handshake_timeouts_total 10909
telemt_upstream_connect_attempt_total 21544
telemt_upstream_connect_success_total 21348
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 21544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29935
telemt_me_reconnect_success_total 18334
telemt_me_reader_eof_total 19390
telemt_me_idle_close_by_peer_total 19390
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 100572
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295665
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1184
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 817
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 447
telemt_pool_swap_total 36
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18902
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18302
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 295601
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 22329118389 (20.80 GB)
telemt_user_octets_to_client{user="hello"} 245259512306 (228.42 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 22
```