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

# Server Metrics 2026-03-19 21:29:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 15098.1 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376570
telemt_connections_bad_total 18549
telemt_connections_current 812
telemt_connections_me_current 812
telemt_handshake_timeouts_total 5556
telemt_upstream_connect_attempt_total 2404
telemt_upstream_connect_success_total 2381
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1626
telemt_me_reconnect_success_total 1614
telemt_me_reader_eof_total 1703
telemt_me_idle_close_by_peer_total 1703
telemt_me_route_drop_no_conn_total 114903
telemt_me_route_drop_channel_closed_total 48
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298874
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1571
telemt_desync_full_logged_total 554
telemt_desync_suppressed_total 1017
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 771
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1653
telemt_me_writer_restored_same_endpoint_total 1601
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 299144
telemt_user_connections_current{user="hello"} 812
telemt_user_octets_from_client{user="hello"} 10972125892 (10.22 GB)
telemt_user_octets_to_client{user="hello"} 113075435920 (105.31 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 31553.1 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2678513
telemt_connections_bad_total 113852
telemt_connections_current 2201
telemt_connections_me_current 2201
telemt_handshake_timeouts_total 52384
telemt_upstream_connect_attempt_total 6408
telemt_upstream_connect_success_total 6310
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 6408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7720
telemt_me_reconnect_success_total 3491
telemt_me_reader_eof_total 3757
telemt_me_idle_close_by_peer_total 3757
telemt_me_route_drop_no_conn_total 1411646
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2283836
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10114
telemt_desync_full_logged_total 3290
telemt_desync_suppressed_total 6824
telemt_desync_frames_bucket_total{bucket="1_2"} 1869
telemt_desync_frames_bucket_total{bucket="3_10"} 3958
telemt_desync_frames_bucket_total{bucket="gt_10"} 4287
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 3658
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3436
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2283716
telemt_user_connections_current{user="hello"} 2201
telemt_user_octets_from_client{user="hello"} 35951185214 (33.48 GB)
telemt_user_octets_to_client{user="hello"} 810398556710 (754.74 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 856
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 31531.0 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2616863
telemt_connections_bad_total 455823
telemt_connections_current 1609
telemt_connections_me_current 1609
telemt_handshake_timeouts_total 32160
telemt_upstream_connect_attempt_total 4863
telemt_upstream_connect_success_total 4828
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4171
telemt_me_reconnect_success_total 3245
telemt_me_reader_eof_total 3366
telemt_me_idle_close_by_peer_total 3365
telemt_me_route_drop_no_conn_total 1841053
telemt_me_route_drop_channel_closed_total 164
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1830805
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6958
telemt_desync_full_logged_total 2092
telemt_desync_suppressed_total 4866
telemt_desync_frames_bucket_total{bucket="1_2"} 1764
telemt_desync_frames_bucket_total{bucket="3_10"} 2628
telemt_desync_frames_bucket_total{bucket="gt_10"} 2566
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 3263
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3244
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 1826743
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 27118693804 (25.26 GB)
telemt_user_octets_to_client{user="hello"} 661143009244 (615.74 GB)
telemt_user_unique_ips_current{user="hello"} 628
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 31518.8 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2288696
telemt_connections_bad_total 94677
telemt_connections_current 1516
telemt_connections_me_current 1516
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 28612
telemt_upstream_connect_attempt_total 35059
telemt_upstream_connect_success_total 33355
telemt_upstream_connect_fail_total 1704
telemt_upstream_connect_attempts_per_request{bucket="1"} 35059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 442
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1704
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6298
telemt_me_reconnect_success_total 3700
telemt_me_reader_eof_total 3836
telemt_me_idle_close_by_peer_total 3835
telemt_me_route_drop_no_conn_total 1801607
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1949850
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7859
telemt_desync_full_logged_total 2448
telemt_desync_suppressed_total 5411
telemt_desync_frames_bucket_total{bucket="1_2"} 1940
telemt_desync_frames_bucket_total{bucket="3_10"} 2855
telemt_desync_frames_bucket_total{bucket="gt_10"} 3064
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 346
telemt_me_writer_removed_unexpected_total 4204
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3696
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 1976793
telemt_user_connections_current{user="hello"} 1516
telemt_user_octets_from_client{user="hello"} 32761117656 (30.51 GB)
telemt_user_octets_to_client{user="hello"} 491792333727 (458.02 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 586
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 85241.8 (23h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5959350
telemt_connections_bad_total 1030194
telemt_connections_current 2037
telemt_connections_me_current 2037
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 108125
telemt_upstream_connect_attempt_total 66461
telemt_upstream_connect_success_total 63959
telemt_upstream_connect_fail_total 2502
telemt_upstream_connect_attempts_per_request{bucket="1"} 66461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2502
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75946
telemt_me_reconnect_success_total 10529
telemt_me_reader_eof_total 11114
telemt_me_idle_close_by_peer_total 11111
telemt_me_route_drop_no_conn_total 2722745
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4222630
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
telemt_desync_total 18560
telemt_desync_full_logged_total 5763
telemt_desync_suppressed_total 12797
telemt_desync_frames_bucket_total{bucket="1_2"} 3199
telemt_desync_frames_bucket_total{bucket="3_10"} 7673
telemt_desync_frames_bucket_total{bucket="gt_10"} 7688
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 10791
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10505
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 4270680
telemt_user_connections_current{user="hello"} 2037
telemt_user_octets_from_client{user="hello"} 66431799203 (61.87 GB)
telemt_user_octets_to_client{user="hello"} 1646912104020 (1.50 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 761
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 31481.8 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612778
telemt_connections_bad_total 48858
telemt_connections_current 449
telemt_connections_me_current 449
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11771
telemt_upstream_connect_attempt_total 8877
telemt_upstream_connect_success_total 8680
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4984
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 553
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4176
telemt_me_reconnect_success_total 4113
telemt_me_reader_eof_total 4279
telemt_me_idle_close_by_peer_total 4278
telemt_me_route_drop_no_conn_total 403018
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490676
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
telemt_desync_total 1340
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 549
telemt_desync_frames_bucket_total{bucket="gt_10"} 584
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 140
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4150
telemt_me_writer_restored_same_endpoint_total 4104
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 506118
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 6699581096 (6.24 GB)
telemt_user_octets_to_client{user="hello"} 113323359566 (105.54 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 31483.3 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1808134
telemt_connections_bad_total 105606
telemt_connections_current 1770
telemt_connections_me_current 1770
telemt_handshake_timeouts_total 32440
telemt_upstream_connect_attempt_total 5192
telemt_upstream_connect_success_total 5153
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 5192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3601
telemt_me_reconnect_success_total 3567
telemt_me_reader_eof_total 3753
telemt_me_idle_close_by_peer_total 3753
telemt_me_route_drop_no_conn_total 679111
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1570744
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8413
telemt_desync_full_logged_total 2640
telemt_desync_suppressed_total 5773
telemt_desync_frames_bucket_total{bucket="1_2"} 1553
telemt_desync_frames_bucket_total{bucket="3_10"} 2938
telemt_desync_frames_bucket_total{bucket="gt_10"} 3922
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3635
telemt_me_writer_restored_same_endpoint_total 3550
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 1569897
telemt_user_connections_current{user="hello"} 1770
telemt_user_octets_from_client{user="hello"} 26777615748 (24.94 GB)
telemt_user_octets_to_client{user="hello"} 773424491908 (720.31 GB)
telemt_user_unique_ips_current{user="hello"} 639
telemt_user_unique_ips_recent_window{user="hello"} 160
```