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

# Server Metrics 2026-03-18 19:44:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15562.3 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398118
telemt_connections_bad_total 23581
telemt_handshake_timeouts_total 8614
telemt_upstream_connect_attempt_total 2811
telemt_upstream_connect_success_total 2808
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 2004
telemt_me_reconnect_success_total 1993
telemt_me_reader_eof_total 2069
telemt_me_idle_close_by_peer_total 2069
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 168791
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344209
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2051
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1470
telemt_desync_frames_bucket_total{bucket="1_2"} 488
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 919
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2029
telemt_me_writer_restored_same_endpoint_total 1975
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 344088
telemt_user_connections_current{user="hello"} 1178
telemt_user_octets_from_client{user="hello"} 6944847400 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 122547221780 (114.13 GB)
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 20390.8 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1931566
telemt_connections_bad_total 133388
telemt_connections_current 3494
telemt_connections_me_current 3494
telemt_handshake_timeouts_total 33263
telemt_upstream_connect_attempt_total 3242
telemt_upstream_connect_success_total 3226
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2205
telemt_me_reconnect_success_total 2188
telemt_me_reader_eof_total 2202
telemt_me_idle_close_by_peer_total 2201
telemt_me_route_drop_no_conn_total 1754760
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1669989
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5757
telemt_desync_full_logged_total 1844
telemt_desync_suppressed_total 3913
telemt_desync_frames_bucket_total{bucket="1_2"} 997
telemt_desync_frames_bucket_total{bucket="3_10"} 2304
telemt_desync_frames_bucket_total{bucket="gt_10"} 2456
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2142
telemt_me_writer_restored_same_endpoint_total 2186
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1665209
telemt_user_connections_current{user="hello"} 3494
telemt_user_octets_from_client{user="hello"} 25704961864 (23.94 GB)
telemt_user_octets_to_client{user="hello"} 545922819248 (508.43 GB)
telemt_user_unique_ips_current{user="hello"} 1134
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 20319.3 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1466748
telemt_connections_bad_total 123124
telemt_connections_current 3012
telemt_connections_me_current 3012
telemt_handshake_timeouts_total 31466
telemt_upstream_connect_attempt_total 2927
telemt_upstream_connect_success_total 2911
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1886
telemt_me_reconnect_success_total 1869
telemt_me_reader_eof_total 1984
telemt_me_idle_close_by_peer_total 1984
telemt_me_route_drop_no_conn_total 597820
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1173780
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5490
telemt_desync_full_logged_total 1707
telemt_desync_suppressed_total 3783
telemt_desync_frames_bucket_total{bucket="1_2"} 1359
telemt_desync_frames_bucket_total{bucket="3_10"} 2080
telemt_desync_frames_bucket_total{bucket="gt_10"} 2051
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 1915
telemt_me_writer_restored_same_endpoint_total 1852
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1173060
telemt_user_connections_current{user="hello"} 3012
telemt_user_octets_from_client{user="hello"} 25320724660 (23.58 GB)
telemt_user_octets_to_client{user="hello"} 569843022368 (530.71 GB)
telemt_user_unique_ips_current{user="hello"} 995
telemt_user_unique_ips_recent_window{user="hello"} 362
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 21033.8 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2114684
telemt_connections_bad_total 54931
telemt_connections_current 2381
telemt_connections_me_current 2381
telemt_handshake_timeouts_total 21544
telemt_upstream_connect_attempt_total 3212
telemt_upstream_connect_success_total 3181
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 3212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2115
telemt_me_reconnect_success_total 2090
telemt_me_reader_eof_total 2169
telemt_me_idle_close_by_peer_total 2168
telemt_me_route_drop_no_conn_total 3657901
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1890847
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7027
telemt_desync_full_logged_total 1792
telemt_desync_suppressed_total 5235
telemt_desync_frames_bucket_total{bucket="1_2"} 1542
telemt_desync_frames_bucket_total{bucket="3_10"} 3291
telemt_desync_frames_bucket_total{bucket="gt_10"} 2194
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2102
telemt_me_writer_restored_same_endpoint_total 2079
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 1890755
telemt_user_connections_current{user="hello"} 2381
telemt_user_octets_from_client{user="hello"} 17258588392 (16.07 GB)
telemt_user_octets_to_client{user="hello"} 311742221508 (290.33 GB)
telemt_user_unique_ips_current{user="hello"} 821
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15548.7 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1133759
telemt_connections_bad_total 205067
telemt_handshake_timeouts_total 10934
telemt_upstream_connect_attempt_total 2796
telemt_upstream_connect_success_total 2709
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 2796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 3989
telemt_me_reconnect_success_total 1893
telemt_me_reader_eof_total 2012
telemt_me_idle_close_by_peer_total 2012
telemt_me_route_drop_no_conn_total 488515
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 830631
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2928
telemt_desync_full_logged_total 1046
telemt_desync_suppressed_total 1882
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 996
telemt_desync_frames_bucket_total{bucket="gt_10"} 1384
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1990
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1867
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 830003
telemt_user_connections_current{user="hello"} 2908
telemt_user_octets_from_client{user="hello"} 14413548712 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 387814561408 (361.18 GB)
telemt_user_unique_ips_current{user="hello"} 996
telemt_user_unique_ips_recent_window{user="hello"} 379
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 20482.0 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337906
telemt_connections_bad_total 10641
telemt_connections_current 730
telemt_connections_me_current 730
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3687
telemt_upstream_connect_attempt_total 7575
telemt_upstream_connect_success_total 7546
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 332150
telemt_me_reconnect_success_total 2680
telemt_me_reader_eof_total 2725
telemt_me_idle_close_by_peer_total 2725
telemt_me_route_drop_no_conn_total 206620
telemt_me_route_drop_channel_closed_total 99
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299807
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 591
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 18
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2635
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2669
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 303492
telemt_user_connections_current{user="hello"} 730
telemt_user_octets_from_client{user="hello"} 5353574025 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 66643115021 (62.07 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 19553.0 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1166399
telemt_connections_bad_total 97117
telemt_connections_current 2986
telemt_connections_me_current 2986
telemt_handshake_timeouts_total 22885
telemt_upstream_connect_attempt_total 3252
telemt_upstream_connect_success_total 3251
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17771
telemt_me_reconnect_success_total 2251
telemt_me_reader_eof_total 2290
telemt_me_idle_close_by_peer_total 2290
telemt_me_route_drop_no_conn_total 535209
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 968692
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4111
telemt_desync_full_logged_total 1391
telemt_desync_suppressed_total 2720
telemt_desync_frames_bucket_total{bucket="1_2"} 922
telemt_desync_frames_bucket_total{bucket="3_10"} 1453
telemt_desync_frames_bucket_total{bucket="gt_10"} 1736
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2231
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2190
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 967479
telemt_user_connections_current{user="hello"} 2986
telemt_user_octets_from_client{user="hello"} 19487339000 (18.15 GB)
telemt_user_octets_to_client{user="hello"} 553983473196 (515.94 GB)
telemt_user_unique_ips_current{user="hello"} 860
telemt_user_unique_ips_recent_window{user="hello"} 321
```