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

# Server Metrics 2026-03-18 21:37:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22310.2 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507208
telemt_connections_bad_total 29272
telemt_handshake_timeouts_total 9791
telemt_upstream_connect_attempt_total 4011
telemt_upstream_connect_success_total 4008
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 2903
telemt_me_reconnect_success_total 2886
telemt_me_reader_eof_total 3015
telemt_me_idle_close_by_peer_total 3015
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 203865
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 431456
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2604
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 1823
telemt_desync_frames_bucket_total{bucket="1_2"} 595
telemt_desync_frames_bucket_total{bucket="3_10"} 834
telemt_desync_frames_bucket_total{bucket="gt_10"} 1175
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2939
telemt_me_writer_restored_same_endpoint_total 2866
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 431274
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 8256847180 (7.69 GB)
telemt_user_octets_to_client{user="hello"} 161173677988 (150.10 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 27138.3 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2264859
telemt_connections_bad_total 158192
telemt_connections_current 2302
telemt_connections_me_current 2302
telemt_handshake_timeouts_total 37388
telemt_upstream_connect_attempt_total 4209
telemt_upstream_connect_success_total 4182
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2815
telemt_me_reconnect_success_total 2795
telemt_me_reader_eof_total 2855
telemt_me_idle_close_by_peer_total 2854
telemt_me_route_drop_no_conn_total 1880204
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1960174
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7106
telemt_desync_full_logged_total 2322
telemt_desync_suppressed_total 4784
telemt_desync_frames_bucket_total{bucket="1_2"} 1232
telemt_desync_frames_bucket_total{bucket="3_10"} 2792
telemt_desync_frames_bucket_total{bucket="gt_10"} 3082
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 2768
telemt_me_writer_restored_same_endpoint_total 2793
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1955561
telemt_user_connections_current{user="hello"} 2302
telemt_user_octets_from_client{user="hello"} 32631839668 (30.39 GB)
telemt_user_octets_to_client{user="hello"} 698851816828 (650.86 GB)
telemt_user_unique_ips_current{user="hello"} 835
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 27066.6 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1743579
telemt_connections_bad_total 146057
telemt_connections_current 1947
telemt_connections_me_current 1947
telemt_handshake_timeouts_total 41528
telemt_upstream_connect_attempt_total 3909
telemt_upstream_connect_success_total 3888
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2535
telemt_me_reconnect_success_total 2514
telemt_me_reader_eof_total 2673
telemt_me_idle_close_by_peer_total 2673
telemt_me_route_drop_no_conn_total 701581
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1407509
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6800
telemt_desync_full_logged_total 2075
telemt_desync_suppressed_total 4725
telemt_desync_frames_bucket_total{bucket="1_2"} 1673
telemt_desync_frames_bucket_total{bucket="3_10"} 2548
telemt_desync_frames_bucket_total{bucket="gt_10"} 2579
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 2574
telemt_me_writer_restored_same_endpoint_total 2497
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1406703
telemt_user_connections_current{user="hello"} 1947
telemt_user_octets_from_client{user="hello"} 29999867972 (27.94 GB)
telemt_user_octets_to_client{user="hello"} 725131765928 (675.33 GB)
telemt_user_unique_ips_current{user="hello"} 699
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 27781.3 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2392920
telemt_connections_bad_total 99348
telemt_connections_current 1569
telemt_connections_me_current 1569
telemt_handshake_timeouts_total 23289
telemt_upstream_connect_attempt_total 4203
telemt_upstream_connect_success_total 4162
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 4203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2793
telemt_me_reconnect_success_total 2763
telemt_me_reader_eof_total 2887
telemt_me_idle_close_by_peer_total 2886
telemt_me_route_drop_no_conn_total 3761182
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2088335
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7984
telemt_desync_full_logged_total 2106
telemt_desync_suppressed_total 5878
telemt_desync_frames_bucket_total{bucket="1_2"} 1764
telemt_desync_frames_bucket_total{bucket="3_10"} 3623
telemt_desync_frames_bucket_total{bucket="gt_10"} 2597
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 2786
telemt_me_writer_restored_same_endpoint_total 2752
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 2088237
telemt_user_connections_current{user="hello"} 1569
telemt_user_octets_from_client{user="hello"} 22094811528 (20.58 GB)
telemt_user_octets_to_client{user="hello"} 407739806428 (379.74 GB)
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22296.1 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1423082
telemt_connections_bad_total 235683
telemt_handshake_timeouts_total 13847
telemt_upstream_connect_attempt_total 4161
telemt_upstream_connect_success_total 4029
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 4161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 8653
telemt_me_reconnect_success_total 2904
telemt_me_reader_eof_total 3157
telemt_me_idle_close_by_peer_total 3157
telemt_me_route_drop_no_conn_total 583778
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1060219
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4255
telemt_desync_full_logged_total 1530
telemt_desync_suppressed_total 2725
telemt_desync_frames_bucket_total{bucket="1_2"} 730
telemt_desync_frames_bucket_total{bucket="3_10"} 1467
telemt_desync_frames_bucket_total{bucket="gt_10"} 2058
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3131
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2878
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 1059580
telemt_user_connections_current{user="hello"} 2005
telemt_user_octets_from_client{user="hello"} 18946392076 (17.65 GB)
telemt_user_octets_to_client{user="hello"} 527679112320 (491.44 GB)
telemt_user_unique_ips_current{user="hello"} 791
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 27228.8 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395318
telemt_connections_bad_total 12622
telemt_connections_current 490
telemt_connections_me_current 490
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4411
telemt_upstream_connect_attempt_total 8782
telemt_upstream_connect_success_total 8744
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 333002
telemt_me_reconnect_success_total 3529
telemt_me_reader_eof_total 3643
telemt_me_idle_close_by_peer_total 3643
telemt_me_route_drop_no_conn_total 230092
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351461
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 827
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 526
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 26
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3502
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3518
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 354970
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 7616440845 (7.09 GB)
telemt_user_octets_to_client{user="hello"} 97228341349 (90.55 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 26300.5 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1409329
telemt_connections_bad_total 108891
telemt_connections_current 1828
telemt_connections_me_current 1828
telemt_handshake_timeouts_total 31493
telemt_upstream_connect_attempt_total 4349
telemt_upstream_connect_success_total 4348
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18521
telemt_me_reconnect_success_total 2995
telemt_me_reader_eof_total 3085
telemt_me_idle_close_by_peer_total 3084
telemt_me_route_drop_no_conn_total 621681
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1181079
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5774
telemt_desync_full_logged_total 1870
telemt_desync_suppressed_total 3904
telemt_desync_frames_bucket_total{bucket="1_2"} 1444
telemt_desync_frames_bucket_total{bucket="3_10"} 1929
telemt_desync_frames_bucket_total{bucket="gt_10"} 2401
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 2987
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2934
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1179762
telemt_user_connections_current{user="hello"} 1828
telemt_user_octets_from_client{user="hello"} 23276126364 (21.68 GB)
telemt_user_octets_to_client{user="hello"} 693683880624 (646.04 GB)
telemt_user_unique_ips_current{user="hello"} 653
telemt_user_unique_ips_recent_window{user="hello"} 177
```