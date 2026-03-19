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

# Server Metrics 2026-03-19 14:50:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 164.9 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8164
telemt_connections_bad_total 1
telemt_connections_current 135
telemt_connections_direct_current 135
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 6019
telemt_upstream_connect_attempt_total 629
telemt_upstream_connect_success_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 627
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 14719431 (14.04 MB)
telemt_user_octets_to_client{user="hello"} 209396340 (199.70 MB)
telemt_user_msgs_from_client{user="hello"} 8262
telemt_user_msgs_to_client{user="hello"} 13787
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 7632.9 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 815256
telemt_connections_bad_total 27969
telemt_connections_current 4093
telemt_connections_me_current 4093
telemt_handshake_timeouts_total 16737
telemt_upstream_connect_attempt_total 2792
telemt_upstream_connect_success_total 2769
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 5321
telemt_me_reconnect_success_total 1106
telemt_me_reader_eof_total 1210
telemt_me_idle_close_by_peer_total 1210
telemt_me_route_drop_no_conn_total 620088
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700079
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2541
telemt_desync_full_logged_total 808
telemt_desync_suppressed_total 1733
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 1105
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 1226
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1051
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 700868
telemt_user_connections_current{user="hello"} 4093
telemt_user_octets_from_client{user="hello"} 8861795338 (8.25 GB)
telemt_user_octets_to_client{user="hello"} 188142227246 (175.22 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1392
telemt_user_unique_ips_recent_window{user="hello"} 650
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 7611.2 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809524
telemt_connections_bad_total 93416
telemt_connections_current 2953
telemt_connections_me_current 2953
telemt_handshake_timeouts_total 7966
telemt_upstream_connect_attempt_total 1287
telemt_upstream_connect_success_total 1275
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1748
telemt_me_reconnect_success_total 843
telemt_me_reader_eof_total 797
telemt_me_idle_close_by_peer_total 796
telemt_me_route_drop_no_conn_total 746593
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613291
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2150
telemt_desync_full_logged_total 571
telemt_desync_suppressed_total 1579
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 794
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 810
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 842
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 610533
telemt_user_connections_current{user="hello"} 2953
telemt_user_octets_from_client{user="hello"} 6307025424 (5.87 GB)
telemt_user_octets_to_client{user="hello"} 160655963748 (149.62 GB)
telemt_user_unique_ips_current{user="hello"} 1074
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 7598.9 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645738
telemt_connections_bad_total 42717
telemt_connections_current 3027
telemt_connections_me_current 3027
telemt_handshake_timeouts_total 10082
telemt_upstream_connect_attempt_total 10339
telemt_upstream_connect_success_total 9843
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 10339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1256
telemt_me_reconnect_success_total 951
telemt_me_reader_eof_total 926
telemt_me_idle_close_by_peer_total 925
telemt_me_route_drop_no_conn_total 433222
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 535007
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2332
telemt_desync_full_logged_total 760
telemt_desync_suppressed_total 1572
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 910
telemt_desync_frames_bucket_total{bucket="gt_10"} 949
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 76
telemt_me_writer_removed_unexpected_total 1065
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 947
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 542986
telemt_user_connections_current{user="hello"} 3027
telemt_user_octets_from_client{user="hello"} 10342452259 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 121848999492 (113.48 GB)
telemt_user_msgs_from_client{user="hello"} 16739
telemt_user_msgs_to_client{user="hello"} 18599
telemt_user_unique_ips_current{user="hello"} 1009
telemt_user_unique_ips_recent_window{user="hello"} 477
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 61322.0 (17h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4283619
telemt_connections_bad_total 800126
telemt_connections_current 3649
telemt_connections_me_current 3649
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 82617
telemt_upstream_connect_attempt_total 62792
telemt_upstream_connect_success_total 60308
telemt_upstream_connect_fail_total 2484
telemt_upstream_connect_attempts_per_request{bucket="1"} 62792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1022
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2484
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 73431
telemt_me_reconnect_success_total 8033
telemt_me_reader_eof_total 8462
telemt_me_idle_close_by_peer_total 8459
telemt_me_route_drop_no_conn_total 2028268
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2939119
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
telemt_desync_total 12696
telemt_desync_full_logged_total 3918
telemt_desync_suppressed_total 8778
telemt_desync_frames_bucket_total{bucket="1_2"} 2163
telemt_desync_frames_bucket_total{bucket="3_10"} 5441
telemt_desync_frames_bucket_total{bucket="gt_10"} 5092
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8247
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 8009
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 2987758
telemt_user_connections_current{user="hello"} 3649
telemt_user_octets_from_client{user="hello"} 47553151543 (44.29 GB)
telemt_user_octets_to_client{user="hello"} 1060651080048 (987.81 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1160
telemt_user_unique_ips_recent_window{user="hello"} 536
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 7563.5 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173703
telemt_connections_bad_total 9158
telemt_connections_current 991
telemt_connections_me_current 991
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 5907
telemt_upstream_connect_attempt_total 4150
telemt_upstream_connect_success_total 4013
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1074
telemt_me_reconnect_success_total 1046
telemt_me_reader_eof_total 1028
telemt_me_idle_close_by_peer_total 1028
telemt_me_route_drop_no_conn_total 114661
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147350
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 420
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 287
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 1017
telemt_me_writer_restored_same_endpoint_total 1037
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 149972
telemt_user_connections_current{user="hello"} 991
telemt_user_octets_from_client{user="hello"} 2172157712 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 38237161218 (35.61 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 7563.5 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518413
telemt_connections_bad_total 35490
telemt_connections_current 3208
telemt_connections_me_current 3208
telemt_handshake_timeouts_total 9740
telemt_upstream_connect_attempt_total 1229
telemt_upstream_connect_success_total 1219
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 800
telemt_me_reconnect_success_total 786
telemt_me_reader_eof_total 812
telemt_me_idle_close_by_peer_total 812
telemt_me_route_drop_no_conn_total 182999
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 446628
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2376
telemt_desync_full_logged_total 721
telemt_desync_suppressed_total 1655
telemt_desync_frames_bucket_total{bucket="1_2"} 457
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 1143
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 811
telemt_me_writer_restored_same_endpoint_total 769
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 446346
telemt_user_connections_current{user="hello"} 3208
telemt_user_octets_from_client{user="hello"} 6144934040 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 188794581812 (175.83 GB)
telemt_user_unique_ips_current{user="hello"} 1044
telemt_user_unique_ips_recent_window{user="hello"} 469
```