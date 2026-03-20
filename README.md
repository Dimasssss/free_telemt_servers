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

# Server Metrics 2026-03-20 02:55:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 34691.1 (9h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 642448
telemt_connections_bad_total 41009
telemt_connections_current 745
telemt_connections_me_current 745
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14554
telemt_upstream_connect_attempt_total 7138
telemt_upstream_connect_success_total 7048
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 7138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4235
telemt_me_reconnect_success_total 4196
telemt_me_reader_eof_total 4434
telemt_me_idle_close_by_peer_total 4433
telemt_me_route_drop_no_conn_total 181110
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509676
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2414
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 1540
telemt_desync_frames_bucket_total{bucket="1_2"} 499
telemt_desync_frames_bucket_total{bucket="3_10"} 865
telemt_desync_frames_bucket_total{bucket="gt_10"} 1050
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4231
telemt_me_writer_restored_same_endpoint_total 4183
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 511109
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 30615023184 (28.51 GB)
telemt_user_octets_to_client{user="hello"} 176417755665 (164.30 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 51145.9 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3131409
telemt_connections_bad_total 157375
telemt_connections_current 1758
telemt_connections_me_current 1758
telemt_handshake_timeouts_total 68903
telemt_upstream_connect_attempt_total 10023
telemt_upstream_connect_success_total 9848
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 10023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10330
telemt_me_reconnect_success_total 6083
telemt_me_reader_eof_total 6509
telemt_me_idle_close_by_peer_total 6509
telemt_me_route_drop_no_conn_total 1530622
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2665255
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11396
telemt_desync_full_logged_total 3755
telemt_desync_suppressed_total 7641
telemt_desync_frames_bucket_total{bucket="1_2"} 2196
telemt_desync_frames_bucket_total{bucket="3_10"} 4450
telemt_desync_frames_bucket_total{bucket="gt_10"} 4750
telemt_pool_swap_total 44
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6285
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6028
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 2665008
telemt_user_connections_current{user="hello"} 1758
telemt_user_octets_from_client{user="hello"} 40575207182 (37.79 GB)
telemt_user_octets_to_client{user="hello"} 990196478474 (922.19 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 761
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 51124.0 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3035504
telemt_connections_bad_total 479674
telemt_connections_current 1462
telemt_connections_me_current 1462
telemt_handshake_timeouts_total 47838
telemt_upstream_connect_attempt_total 8331
telemt_upstream_connect_success_total 8273
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 8331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6672
telemt_me_reconnect_success_total 5737
telemt_me_reader_eof_total 6028
telemt_me_idle_close_by_peer_total 6027
telemt_me_route_drop_no_conn_total 1943100
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2097820
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7876
telemt_desync_full_logged_total 2408
telemt_desync_suppressed_total 5468
telemt_desync_frames_bucket_total{bucket="1_2"} 1927
telemt_desync_frames_bucket_total{bucket="3_10"} 2983
telemt_desync_frames_bucket_total{bucket="gt_10"} 2966
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 71
telemt_me_writer_removed_unexpected_total 5795
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5736
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2093411
telemt_user_connections_current{user="hello"} 1462
telemt_user_octets_from_client{user="hello"} 30665021536 (28.56 GB)
telemt_user_octets_to_client{user="hello"} 808158081624 (752.66 GB)
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 51111.9 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2709798
telemt_connections_bad_total 201100
telemt_connections_current 1288
telemt_connections_me_current 1288
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 32071
telemt_upstream_connect_attempt_total 56214
telemt_upstream_connect_success_total 51912
telemt_upstream_connect_fail_total 4302
telemt_upstream_connect_attempts_per_request{bucket="1"} 56214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 532
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4302
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8983
telemt_me_reconnect_success_total 6127
telemt_me_reader_eof_total 6381
telemt_me_idle_close_by_peer_total 6380
telemt_me_route_drop_no_conn_total 1882222
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2200219
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8513
telemt_desync_full_logged_total 2706
telemt_desync_suppressed_total 5807
telemt_desync_frames_bucket_total{bucket="1_2"} 2101
telemt_desync_frames_bucket_total{bucket="3_10"} 3100
telemt_desync_frames_bucket_total{bucket="gt_10"} 3312
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6763
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6123
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 2242297
telemt_user_connections_current{user="hello"} 1288
telemt_user_octets_from_client{user="hello"} 36284411809 (33.79 GB)
telemt_user_octets_to_client{user="hello"} 639133649549 (595.24 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 104835.2 (29h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6363327
telemt_connections_bad_total 1055683
telemt_connections_current 1420
telemt_connections_me_current 1420
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 115069
telemt_upstream_connect_attempt_total 128329
telemt_upstream_connect_success_total 95041
telemt_upstream_connect_fail_total 33288
telemt_upstream_connect_attempts_per_request{bucket="1"} 128329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1436
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33288
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79170
telemt_me_reconnect_success_total 13498
telemt_me_reader_eof_total 14533
telemt_me_idle_close_by_peer_total 14519
telemt_me_route_drop_no_conn_total 2819740
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4520001
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
telemt_desync_total 19742
telemt_desync_full_logged_total 6266
telemt_desync_suppressed_total 13476
telemt_desync_frames_bucket_total{bucket="1_2"} 3484
telemt_desync_frames_bucket_total{bucket="3_10"} 8146
telemt_desync_frames_bucket_total{bucket="gt_10"} 8112
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 13810
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13473
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 4595224
telemt_user_connections_current{user="hello"} 1420
telemt_user_octets_from_client{user="hello"} 73225631736 (68.20 GB)
telemt_user_octets_to_client{user="hello"} 1773827324412 (1.61 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 595
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 51075.0 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 917966
telemt_connections_bad_total 82363
telemt_connections_current 691
telemt_connections_me_current 691
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13222
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
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
telemt_me_route_drop_no_conn_total 472449
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
telemt_desync_total 1411
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 876
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 589
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
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
telemt_user_connections_total{user="hello"} 770647
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 7706830731 (7.18 GB)
telemt_user_octets_to_client{user="hello"} 146576368358 (136.51 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 51076.4 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2098425
telemt_connections_bad_total 124135
telemt_connections_current 1372
telemt_connections_me_current 1372
telemt_handshake_timeouts_total 38809
telemt_upstream_connect_attempt_total 9185
telemt_upstream_connect_success_total 9122
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 9185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6621
telemt_me_reconnect_success_total 6576
telemt_me_reader_eof_total 6942
telemt_me_idle_close_by_peer_total 6942
telemt_me_route_drop_no_conn_total 761200
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1790685
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9392
telemt_desync_full_logged_total 3025
telemt_desync_suppressed_total 6367
telemt_desync_frames_bucket_total{bucket="1_2"} 1788
telemt_desync_frames_bucket_total{bucket="3_10"} 3292
telemt_desync_frames_bucket_total{bucket="gt_10"} 4312
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6671
telemt_me_writer_restored_same_endpoint_total 6559
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 1789793
telemt_user_connections_current{user="hello"} 1372
telemt_user_octets_from_client{user="hello"} 30437378164 (28.35 GB)
telemt_user_octets_to_client{user="hello"} 916253079196 (853.33 GB)
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 113
```