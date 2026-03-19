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

# Server Metrics 2026-03-19 21:54:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 16630.6 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 394484
telemt_connections_bad_total 19910
telemt_connections_current 817
telemt_connections_me_current 817
telemt_handshake_timeouts_total 5765
telemt_upstream_connect_attempt_total 2725
telemt_upstream_connect_success_total 2701
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1860
telemt_me_reconnect_success_total 1847
telemt_me_reader_eof_total 1953
telemt_me_idle_close_by_peer_total 1953
telemt_me_route_drop_no_conn_total 119856
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313843
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1701
telemt_desync_full_logged_total 590
telemt_desync_suppressed_total 1111
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 529
telemt_desync_frames_bucket_total{bucket="gt_10"} 817
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1887
telemt_me_writer_restored_same_endpoint_total 1834
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 314113
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 11131936356 (10.37 GB)
telemt_user_octets_to_client{user="hello"} 116953663828 (108.92 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 33085.6 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2730049
telemt_connections_bad_total 117307
telemt_connections_current 1939
telemt_connections_me_current 1939
telemt_handshake_timeouts_total 53829
telemt_upstream_connect_attempt_total 6763
telemt_upstream_connect_success_total 6657
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 6763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7998
telemt_me_reconnect_success_total 3768
telemt_me_reader_eof_total 4048
telemt_me_idle_close_by_peer_total 4048
telemt_me_route_drop_no_conn_total 1426504
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2328686
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10323
telemt_desync_full_logged_total 3358
telemt_desync_suppressed_total 6965
telemt_desync_frames_bucket_total{bucket="1_2"} 1923
telemt_desync_frames_bucket_total{bucket="3_10"} 4026
telemt_desync_frames_bucket_total{bucket="gt_10"} 4374
telemt_pool_swap_total 25
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 3936
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3713
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 2328563
telemt_user_connections_current{user="hello"} 1939
telemt_user_octets_from_client{user="hello"} 36701586294 (34.18 GB)
telemt_user_octets_to_client{user="hello"} 829232721682 (772.28 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 780
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 33063.8 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2658197
telemt_connections_bad_total 456991
telemt_connections_current 1455
telemt_connections_me_current 1455
telemt_handshake_timeouts_total 33402
telemt_upstream_connect_attempt_total 5156
telemt_upstream_connect_success_total 5114
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 5156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4377
telemt_me_reconnect_success_total 3450
telemt_me_reader_eof_total 3585
telemt_me_idle_close_by_peer_total 3584
telemt_me_route_drop_no_conn_total 1851671
telemt_me_route_drop_channel_closed_total 166
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1858825
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7192
telemt_desync_full_logged_total 2158
telemt_desync_suppressed_total 5034
telemt_desync_frames_bucket_total{bucket="1_2"} 1796
telemt_desync_frames_bucket_total{bucket="3_10"} 2743
telemt_desync_frames_bucket_total{bucket="gt_10"} 2653
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 60
telemt_me_writer_removed_unexpected_total 3473
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3449
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1854763
telemt_user_connections_current{user="hello"} 1455
telemt_user_octets_from_client{user="hello"} 28160208336 (26.23 GB)
telemt_user_octets_to_client{user="hello"} 678716107396 (632.10 GB)
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 33051.9 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2329448
telemt_connections_bad_total 96541
telemt_connections_current 1487
telemt_connections_me_current 1487
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29244
telemt_upstream_connect_attempt_total 35384
telemt_upstream_connect_success_total 33658
telemt_upstream_connect_fail_total 1726
telemt_upstream_connect_attempts_per_request{bucket="1"} 35384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5425
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 449
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1726
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6528
telemt_me_reconnect_success_total 3914
telemt_me_reader_eof_total 4052
telemt_me_idle_close_by_peer_total 4051
telemt_me_route_drop_no_conn_total 1814182
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1981994
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7953
telemt_desync_full_logged_total 2484
telemt_desync_suppressed_total 5469
telemt_desync_frames_bucket_total{bucket="1_2"} 1957
telemt_desync_frames_bucket_total{bucket="3_10"} 2892
telemt_desync_frames_bucket_total{bucket="gt_10"} 3104
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 347
telemt_me_writer_removed_unexpected_total 4428
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3910
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 2008927
telemt_user_connections_current{user="hello"} 1487
telemt_user_octets_from_client{user="hello"} 33052557304 (30.78 GB)
telemt_user_octets_to_client{user="hello"} 512632155283 (477.43 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 86774.7 (24h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5999779
telemt_connections_bad_total 1031792
telemt_connections_current 1688
telemt_connections_me_current 1688
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 108671
telemt_upstream_connect_attempt_total 66764
telemt_upstream_connect_success_total 64258
telemt_upstream_connect_fail_total 2506
telemt_upstream_connect_attempts_per_request{bucket="1"} 66764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2506
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76159
telemt_me_reconnect_success_total 10741
telemt_me_reader_eof_total 11341
telemt_me_idle_close_by_peer_total 11338
telemt_me_route_drop_no_conn_total 2735645
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4257282
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
telemt_desync_total 18767
telemt_desync_full_logged_total 5828
telemt_desync_suppressed_total 12939
telemt_desync_frames_bucket_total{bucket="1_2"} 3263
telemt_desync_frames_bucket_total{bucket="3_10"} 7725
telemt_desync_frames_bucket_total{bucket="gt_10"} 7779
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 11005
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10717
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 4305331
telemt_user_connections_current{user="hello"} 1688
telemt_user_octets_from_client{user="hello"} 66787678147 (62.20 GB)
telemt_user_octets_to_client{user="hello"} 1661993164040 (1.51 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 33015.1 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 621893
telemt_connections_bad_total 49112
telemt_connections_current 424
telemt_connections_me_current 424
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11896
telemt_upstream_connect_attempt_total 9226
telemt_upstream_connect_success_total 9013
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 9226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5178
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 564
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4437
telemt_me_reconnect_success_total 4357
telemt_me_reader_eof_total 4536
telemt_me_idle_close_by_peer_total 4534
telemt_me_route_drop_no_conn_total 424558
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512373
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
telemt_desync_total 1350
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 845
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 26
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 144
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4397
telemt_me_writer_restored_same_endpoint_total 4348
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 514363
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 6788433864 (6.32 GB)
telemt_user_octets_to_client{user="hello"} 118272564682 (110.15 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 33016.3 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1843579
telemt_connections_bad_total 108197
telemt_connections_current 1575
telemt_connections_me_current 1575
telemt_handshake_timeouts_total 33482
telemt_upstream_connect_attempt_total 5511
telemt_upstream_connect_success_total 5470
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 5511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3832
telemt_me_reconnect_success_total 3797
telemt_me_reader_eof_total 3996
telemt_me_idle_close_by_peer_total 3996
telemt_me_route_drop_no_conn_total 689876
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1598904
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8587
telemt_desync_full_logged_total 2693
telemt_desync_suppressed_total 5894
telemt_desync_frames_bucket_total{bucket="1_2"} 1575
telemt_desync_frames_bucket_total{bucket="3_10"} 2998
telemt_desync_frames_bucket_total{bucket="gt_10"} 4014
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 3867
telemt_me_writer_restored_same_endpoint_total 3780
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1598052
telemt_user_connections_current{user="hello"} 1575
telemt_user_octets_from_client{user="hello"} 27317090596 (25.44 GB)
telemt_user_octets_to_client{user="hello"} 796032843796 (741.36 GB)
telemt_user_unique_ips_current{user="hello"} 567
telemt_user_unique_ips_recent_window{user="hello"} 117
```