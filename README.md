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

# Server Metrics 2026-03-18 21:32:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22003.6 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503547
telemt_connections_bad_total 29007
telemt_handshake_timeouts_total 9766
telemt_upstream_connect_attempt_total 3980
telemt_upstream_connect_success_total 3977
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 2872
telemt_me_reconnect_success_total 2855
telemt_me_reader_eof_total 2983
telemt_me_idle_close_by_peer_total 2983
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 202811
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428237
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2592
telemt_desync_full_logged_total 775
telemt_desync_suppressed_total 1817
telemt_desync_frames_bucket_total{bucket="1_2"} 593
telemt_desync_frames_bucket_total{bucket="3_10"} 830
telemt_desync_frames_bucket_total{bucket="gt_10"} 1169
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2907
telemt_me_writer_restored_same_endpoint_total 2835
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 428055
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 8232692260 (7.67 GB)
telemt_user_octets_to_client{user="hello"} 159075718380 (148.15 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 26831.9 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2254079
telemt_connections_bad_total 157861
telemt_connections_current 2421
telemt_connections_me_current 2421
telemt_handshake_timeouts_total 37294
telemt_upstream_connect_attempt_total 4145
telemt_upstream_connect_success_total 4118
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2794
telemt_me_reconnect_success_total 2774
telemt_me_reader_eof_total 2834
telemt_me_idle_close_by_peer_total 2833
telemt_me_route_drop_no_conn_total 1875768
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1950587
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7060
telemt_desync_full_logged_total 2305
telemt_desync_suppressed_total 4755
telemt_desync_frames_bucket_total{bucket="1_2"} 1227
telemt_desync_frames_bucket_total{bucket="3_10"} 2774
telemt_desync_frames_bucket_total{bucket="gt_10"} 3059
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2747
telemt_me_writer_restored_same_endpoint_total 2772
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1945976
telemt_user_connections_current{user="hello"} 2421
telemt_user_octets_from_client{user="hello"} 32182870248 (29.97 GB)
telemt_user_octets_to_client{user="hello"} 692150527836 (644.62 GB)
telemt_user_unique_ips_current{user="hello"} 856
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 26760.4 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1733510
telemt_connections_bad_total 144307
telemt_connections_current 1993
telemt_connections_me_current 1993
telemt_handshake_timeouts_total 41336
telemt_upstream_connect_attempt_total 3870
telemt_upstream_connect_success_total 3849
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2523
telemt_me_reconnect_success_total 2502
telemt_me_reader_eof_total 2661
telemt_me_idle_close_by_peer_total 2661
telemt_me_route_drop_no_conn_total 697911
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1399558
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6782
telemt_desync_full_logged_total 2070
telemt_desync_suppressed_total 4712
telemt_desync_frames_bucket_total{bucket="1_2"} 1670
telemt_desync_frames_bucket_total{bucket="3_10"} 2540
telemt_desync_frames_bucket_total{bucket="gt_10"} 2572
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 2562
telemt_me_writer_restored_same_endpoint_total 2485
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1398753
telemt_user_connections_current{user="hello"} 1993
telemt_user_octets_from_client{user="hello"} 29927088248 (27.87 GB)
telemt_user_octets_to_client{user="hello"} 718680740968 (669.32 GB)
telemt_user_unique_ips_current{user="hello"} 717
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 27475.0 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2381896
telemt_connections_bad_total 95754
telemt_connections_current 1573
telemt_connections_me_current 1573
telemt_handshake_timeouts_total 23178
telemt_upstream_connect_attempt_total 4180
telemt_upstream_connect_success_total 4139
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 4180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2770
telemt_me_reconnect_success_total 2740
telemt_me_reader_eof_total 2864
telemt_me_idle_close_by_peer_total 2863
telemt_me_route_drop_no_conn_total 3758539
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2082441
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7976
telemt_desync_full_logged_total 2102
telemt_desync_suppressed_total 5874
telemt_desync_frames_bucket_total{bucket="1_2"} 1761
telemt_desync_frames_bucket_total{bucket="3_10"} 3619
telemt_desync_frames_bucket_total{bucket="gt_10"} 2596
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 2763
telemt_me_writer_restored_same_endpoint_total 2729
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 2082342
telemt_user_connections_current{user="hello"} 1573
telemt_user_octets_from_client{user="hello"} 22006511212 (20.50 GB)
telemt_user_octets_to_client{user="hello"} 404812358936 (377.01 GB)
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21989.8 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1413999
telemt_connections_bad_total 235352
telemt_handshake_timeouts_total 13630
telemt_upstream_connect_attempt_total 4115
telemt_upstream_connect_success_total 3983
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 4115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 8607
telemt_me_reconnect_success_total 2858
telemt_me_reader_eof_total 3111
telemt_me_idle_close_by_peer_total 3111
telemt_me_route_drop_no_conn_total 580479
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1052505
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4141
telemt_desync_full_logged_total 1512
telemt_desync_suppressed_total 2629
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 1411
telemt_desync_frames_bucket_total{bucket="gt_10"} 2016
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3085
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2832
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 1051866
telemt_user_connections_current{user="hello"} 2141
telemt_user_octets_from_client{user="hello"} 18659375124 (17.38 GB)
telemt_user_octets_to_client{user="hello"} 521983705788 (486.14 GB)
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 26922.4 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392882
telemt_connections_bad_total 12141
telemt_connections_current 485
telemt_connections_me_current 485
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4301
telemt_upstream_connect_attempt_total 8687
telemt_upstream_connect_success_total 8650
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 332951
telemt_me_reconnect_success_total 3478
telemt_me_reader_eof_total 3584
telemt_me_idle_close_by_peer_total 3584
telemt_me_route_drop_no_conn_total 229224
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349656
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 824
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 524
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3451
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3467
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 353176
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 7595453745 (7.07 GB)
telemt_user_octets_to_client{user="hello"} 96096618645 (89.50 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 25994.2 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1401989
telemt_connections_bad_total 108473
telemt_connections_current 1861
telemt_connections_me_current 1861
telemt_handshake_timeouts_total 31396
telemt_upstream_connect_attempt_total 4260
telemt_upstream_connect_success_total 4259
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18475
telemt_me_reconnect_success_total 2950
telemt_me_reader_eof_total 3032
telemt_me_idle_close_by_peer_total 3031
telemt_me_route_drop_no_conn_total 619011
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1174331
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5719
telemt_desync_full_logged_total 1851
telemt_desync_suppressed_total 3868
telemt_desync_frames_bucket_total{bucket="1_2"} 1424
telemt_desync_frames_bucket_total{bucket="3_10"} 1918
telemt_desync_frames_bucket_total{bucket="gt_10"} 2377
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2940
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2889
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1173014
telemt_user_connections_current{user="hello"} 1861
telemt_user_octets_from_client{user="hello"} 23177261004 (21.59 GB)
telemt_user_octets_to_client{user="hello"} 688456604372 (641.18 GB)
telemt_user_unique_ips_current{user="hello"} 668
telemt_user_unique_ips_recent_window{user="hello"} 201
```