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

# Server Metrics 2026-03-19 09:22:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 41658.2 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 851206
telemt_connections_bad_total 80037
telemt_connections_current 1592
telemt_connections_me_current 1592
telemt_handshake_timeouts_total 33346
telemt_upstream_connect_attempt_total 7965
telemt_upstream_connect_success_total 7826
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 7965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6881
telemt_me_reconnect_success_total 5725
telemt_me_reader_eof_total 6070
telemt_me_idle_close_by_peer_total 6069
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 290860
telemt_me_route_drop_channel_closed_total 112
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 662854
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4107
telemt_desync_full_logged_total 1227
telemt_desync_suppressed_total 2880
telemt_desync_frames_bucket_total{bucket="1_2"} 1370
telemt_desync_frames_bucket_total{bucket="3_10"} 1506
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5828
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5706
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 657313
telemt_user_connections_current{user="hello"} 1592
telemt_user_octets_from_client{user="hello"} 10248677884 (9.54 GB)
telemt_user_octets_to_client{user="hello"} 214097891012 (199.39 GB)
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 41660.8 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2093173
telemt_connections_bad_total 111387
telemt_connections_current 4252
telemt_connections_me_current 4252
telemt_handshake_timeouts_total 46675
telemt_upstream_connect_attempt_total 7967
telemt_upstream_connect_success_total 7818
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 7967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8042
telemt_me_reconnect_success_total 5697
telemt_me_reader_eof_total 6067
telemt_me_idle_close_by_peer_total 6067
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 938228
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1744166
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7750
telemt_desync_full_logged_total 2618
telemt_desync_suppressed_total 5132
telemt_desync_frames_bucket_total{bucket="1_2"} 1411
telemt_desync_frames_bucket_total{bucket="3_10"} 2986
telemt_desync_frames_bucket_total{bucket="gt_10"} 3353
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5870
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 5675
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 1743935
telemt_user_connections_current{user="hello"} 4252
telemt_user_octets_from_client{user="hello"} 28536838728 (26.58 GB)
telemt_user_octets_to_client{user="hello"} 649534153444 (604.93 GB)
telemt_user_unique_ips_current{user="hello"} 1430
telemt_user_unique_ips_recent_window{user="hello"} 647
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 41658.1 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1783975
telemt_connections_bad_total 214364
telemt_connections_current 3083
telemt_connections_me_current 3083
telemt_handshake_timeouts_total 43883
telemt_upstream_connect_attempt_total 7460
telemt_upstream_connect_success_total 7460
telemt_upstream_connect_attempts_per_request{bucket="1"} 7460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5373
telemt_me_reconnect_success_total 5340
telemt_me_reader_eof_total 5655
telemt_me_idle_close_by_peer_total 5655
telemt_me_route_drop_no_conn_total 837903
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1386666
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6308
telemt_desync_full_logged_total 1965
telemt_desync_suppressed_total 4343
telemt_desync_frames_bucket_total{bucket="1_2"} 1436
telemt_desync_frames_bucket_total{bucket="3_10"} 2273
telemt_desync_frames_bucket_total{bucket="gt_10"} 2599
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 5435
telemt_me_writer_restored_same_endpoint_total 5324
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 1385319
telemt_user_connections_current{user="hello"} 3083
telemt_user_octets_from_client{user="hello"} 21532629384 (20.05 GB)
telemt_user_octets_to_client{user="hello"} 645311950940 (600.99 GB)
telemt_user_unique_ips_current{user="hello"} 1054
telemt_user_unique_ips_recent_window{user="hello"} 479
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 41711.3 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1858816
telemt_connections_bad_total 100875
telemt_connections_current 3183
telemt_connections_me_current 3183
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 47027
telemt_upstream_connect_attempt_total 15672
telemt_upstream_connect_success_total 15560
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 15672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7693
telemt_me_reconnect_success_total 5283
telemt_me_reader_eof_total 5619
telemt_me_idle_close_by_peer_total 5618
telemt_me_route_drop_no_conn_total 935822
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1380436
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5027
telemt_desync_full_logged_total 1709
telemt_desync_suppressed_total 3318
telemt_desync_frames_bucket_total{bucket="1_2"} 1032
telemt_desync_frames_bucket_total{bucket="3_10"} 1964
telemt_desync_frames_bucket_total{bucket="gt_10"} 2031
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5552
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5259
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 1387101
telemt_user_connections_current{user="hello"} 3183
telemt_user_octets_from_client{user="hello"} 16587493044 (15.45 GB)
telemt_user_octets_to_client{user="hello"} 404708528910 (376.91 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1025
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 41654.6 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2150918
telemt_connections_bad_total 525321
telemt_connections_current 3561
telemt_connections_me_current 3561
telemt_handshake_timeouts_total 45596
telemt_upstream_connect_attempt_total 7239
telemt_upstream_connect_success_total 7188
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 7239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5121
telemt_me_reconnect_success_total 5079
telemt_me_reader_eof_total 5385
telemt_me_idle_close_by_peer_total 5385
telemt_me_route_drop_no_conn_total 613371
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1368028
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6394
telemt_desync_full_logged_total 1994
telemt_desync_suppressed_total 4400
telemt_desync_frames_bucket_total{bucket="1_2"} 1280
telemt_desync_frames_bucket_total{bucket="3_10"} 2822
telemt_desync_frames_bucket_total{bucket="gt_10"} 2292
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5152
telemt_me_writer_restored_same_endpoint_total 5055
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1367242
telemt_user_connections_current{user="hello"} 3561
telemt_user_octets_from_client{user="hello"} 25965161416 (24.18 GB)
telemt_user_octets_to_client{user="hello"} 609592353040 (567.73 GB)
telemt_user_unique_ips_current{user="hello"} 1213
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 41666.5 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381575
telemt_connections_bad_total 17548
telemt_connections_current 959
telemt_connections_me_current 959
telemt_handshake_timeouts_total 3122
telemt_upstream_connect_attempt_total 10593
telemt_upstream_connect_success_total 10321
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 10592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13593
telemt_me_reconnect_success_total 8208
telemt_me_reader_eof_total 8708
telemt_me_idle_close_by_peer_total 8708
telemt_me_route_drop_no_conn_total 195512
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341485
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 538
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 193
telemt_me_writer_removed_unexpected_total 8442
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8178
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 341450
telemt_user_connections_current{user="hello"} 959
telemt_user_octets_from_client{user="hello"} 4912928728 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 139391584948 (129.82 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 41657.0 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1452588
telemt_connections_bad_total 128576
telemt_connections_current 3088
telemt_connections_me_current 3088
telemt_handshake_timeouts_total 63540
telemt_upstream_connect_attempt_total 8491
telemt_upstream_connect_success_total 8490
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7720
telemt_me_reconnect_success_total 6373
telemt_me_reader_eof_total 6754
telemt_me_idle_close_by_peer_total 6753
telemt_me_route_drop_no_conn_total 573641
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1205785
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6899
telemt_desync_full_logged_total 2261
telemt_desync_suppressed_total 4638
telemt_desync_frames_bucket_total{bucket="1_2"} 1299
telemt_desync_frames_bucket_total{bucket="3_10"} 2599
telemt_desync_frames_bucket_total{bucket="gt_10"} 3001
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6489
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6358
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 1204672
telemt_user_connections_current{user="hello"} 3088
telemt_user_octets_from_client{user="hello"} 16647234820 (15.50 GB)
telemt_user_octets_to_client{user="hello"} 592273402112 (551.60 GB)
telemt_user_unique_ips_current{user="hello"} 1019
telemt_user_unique_ips_recent_window{user="hello"} 434
```