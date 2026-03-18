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

# Server Metrics 2026-03-18 21:42:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22617.2 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512613
telemt_connections_bad_total 31231
telemt_handshake_timeouts_total 9861
telemt_upstream_connect_attempt_total 4083
telemt_upstream_connect_success_total 4080
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 2932
telemt_me_reconnect_success_total 2915
telemt_me_reader_eof_total 3046
telemt_me_idle_close_by_peer_total 3046
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 204990
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434701
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2635
telemt_desync_full_logged_total 791
telemt_desync_suppressed_total 1844
telemt_desync_frames_bucket_total{bucket="1_2"} 602
telemt_desync_frames_bucket_total{bucket="3_10"} 844
telemt_desync_frames_bucket_total{bucket="gt_10"} 1189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2968
telemt_me_writer_restored_same_endpoint_total 2895
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 434519
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 8294049088 (7.72 GB)
telemt_user_octets_to_client{user="hello"} 162959310552 (151.77 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 27445.1 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2276473
telemt_connections_bad_total 160370
telemt_connections_current 2234
telemt_connections_me_current 2234
telemt_handshake_timeouts_total 37449
telemt_upstream_connect_attempt_total 4262
telemt_upstream_connect_success_total 4235
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2868
telemt_me_reconnect_success_total 2847
telemt_me_reader_eof_total 2911
telemt_me_idle_close_by_peer_total 2910
telemt_me_route_drop_no_conn_total 1884195
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1968861
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7114
telemt_desync_full_logged_total 2327
telemt_desync_suppressed_total 4787
telemt_desync_frames_bucket_total{bucket="1_2"} 1235
telemt_desync_frames_bucket_total{bucket="3_10"} 2796
telemt_desync_frames_bucket_total{bucket="gt_10"} 3083
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 2820
telemt_me_writer_restored_same_endpoint_total 2845
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1964249
telemt_user_connections_current{user="hello"} 2234
telemt_user_octets_from_client{user="hello"} 32757801696 (30.51 GB)
telemt_user_octets_to_client{user="hello"} 704385636580 (656.01 GB)
telemt_user_unique_ips_current{user="hello"} 807
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 27373.5 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1752829
telemt_connections_bad_total 147599
telemt_connections_current 1793
telemt_connections_me_current 1793
telemt_handshake_timeouts_total 41697
telemt_upstream_connect_attempt_total 3982
telemt_upstream_connect_success_total 3961
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2592
telemt_me_reconnect_success_total 2571
telemt_me_reader_eof_total 2734
telemt_me_idle_close_by_peer_total 2734
telemt_me_route_drop_no_conn_total 705825
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1414788
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6823
telemt_desync_full_logged_total 2086
telemt_desync_suppressed_total 4737
telemt_desync_frames_bucket_total{bucket="1_2"} 1679
telemt_desync_frames_bucket_total{bucket="3_10"} 2556
telemt_desync_frames_bucket_total{bucket="gt_10"} 2588
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 2631
telemt_me_writer_restored_same_endpoint_total 2554
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1413982
telemt_user_connections_current{user="hello"} 1793
telemt_user_octets_from_client{user="hello"} 30104207096 (28.04 GB)
telemt_user_octets_to_client{user="hello"} 730813486700 (680.62 GB)
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 28088.0 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2402183
telemt_connections_bad_total 102745
telemt_connections_current 1484
telemt_connections_me_current 1484
telemt_handshake_timeouts_total 23371
telemt_upstream_connect_attempt_total 4292
telemt_upstream_connect_success_total 4249
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 4292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2837
telemt_me_reconnect_success_total 2807
telemt_me_reader_eof_total 2935
telemt_me_idle_close_by_peer_total 2934
telemt_me_route_drop_no_conn_total 3763744
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2093731
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8008
telemt_desync_full_logged_total 2111
telemt_desync_suppressed_total 5897
telemt_desync_frames_bucket_total{bucket="1_2"} 1768
telemt_desync_frames_bucket_total{bucket="3_10"} 3634
telemt_desync_frames_bucket_total{bucket="gt_10"} 2606
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 2830
telemt_me_writer_restored_same_endpoint_total 2796
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 2093634
telemt_user_connections_current{user="hello"} 1484
telemt_user_octets_from_client{user="hello"} 22151329536 (20.63 GB)
telemt_user_octets_to_client{user="hello"} 411021750304 (382.79 GB)
telemt_user_unique_ips_current{user="hello"} 587
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22602.8 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1431575
telemt_connections_bad_total 236260
telemt_handshake_timeouts_total 13984
telemt_upstream_connect_attempt_total 4238
telemt_upstream_connect_success_total 4104
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 4238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 8688
telemt_me_reconnect_success_total 2939
telemt_me_reader_eof_total 3194
telemt_me_idle_close_by_peer_total 3194
telemt_me_route_drop_no_conn_total 586736
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1067248
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4304
telemt_desync_full_logged_total 1548
telemt_desync_suppressed_total 2756
telemt_desync_frames_bucket_total{bucket="1_2"} 744
telemt_desync_frames_bucket_total{bucket="3_10"} 1490
telemt_desync_frames_bucket_total{bucket="gt_10"} 2070
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3168
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2913
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 1066608
telemt_user_connections_current{user="hello"} 1880
telemt_user_octets_from_client{user="hello"} 19270324668 (17.95 GB)
telemt_user_octets_to_client{user="hello"} 532449822396 (495.88 GB)
telemt_user_unique_ips_current{user="hello"} 754
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 27535.5 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398144
telemt_connections_bad_total 13417
telemt_connections_current 448
telemt_connections_me_current 448
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4584
telemt_upstream_connect_attempt_total 8826
telemt_upstream_connect_success_total 8788
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4241
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 333046
telemt_me_reconnect_success_total 3573
telemt_me_reader_eof_total 3689
telemt_me_idle_close_by_peer_total 3689
telemt_me_route_drop_no_conn_total 230910
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353249
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 834
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 26
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3548
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3562
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 356759
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 7630474381 (7.11 GB)
telemt_user_octets_to_client{user="hello"} 98214748965 (91.47 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 26607.2 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1416464
telemt_connections_bad_total 110007
telemt_connections_current 1791
telemt_connections_me_current 1791
telemt_handshake_timeouts_total 31586
telemt_upstream_connect_attempt_total 4396
telemt_upstream_connect_success_total 4395
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18568
telemt_me_reconnect_success_total 3042
telemt_me_reader_eof_total 3132
telemt_me_idle_close_by_peer_total 3131
telemt_me_route_drop_no_conn_total 624007
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1186920
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5841
telemt_desync_full_logged_total 1889
telemt_desync_suppressed_total 3952
telemt_desync_frames_bucket_total{bucket="1_2"} 1468
telemt_desync_frames_bucket_total{bucket="3_10"} 1949
telemt_desync_frames_bucket_total{bucket="gt_10"} 2424
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3034
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2981
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1185603
telemt_user_connections_current{user="hello"} 1791
telemt_user_octets_from_client{user="hello"} 23414526008 (21.81 GB)
telemt_user_octets_to_client{user="hello"} 698328517048 (650.37 GB)
telemt_user_unique_ips_current{user="hello"} 631
telemt_user_unique_ips_recent_window{user="hello"} 173
```