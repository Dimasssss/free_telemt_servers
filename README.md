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

# Server Metrics 2026-03-19 21:13:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 14180.9 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364267
telemt_connections_bad_total 17734
telemt_connections_current 875
telemt_connections_me_current 875
telemt_handshake_timeouts_total 5408
telemt_upstream_connect_attempt_total 2243
telemt_upstream_connect_success_total 2221
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1508
telemt_me_reconnect_success_total 1498
telemt_me_reader_eof_total 1579
telemt_me_idle_close_by_peer_total 1579
telemt_me_route_drop_no_conn_total 111048
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288373
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1501
telemt_desync_full_logged_total 524
telemt_desync_suppressed_total 977
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1533
telemt_me_writer_restored_same_endpoint_total 1485
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 288628
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 10826331772 (10.08 GB)
telemt_user_octets_to_client{user="hello"} 106093028720 (98.81 GB)
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 30636.4 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2645152
telemt_connections_bad_total 112256
telemt_connections_current 2489
telemt_connections_me_current 2489
telemt_handshake_timeouts_total 51461
telemt_upstream_connect_attempt_total 6243
telemt_upstream_connect_success_total 6147
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 6243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7611
telemt_me_reconnect_success_total 3383
telemt_me_reader_eof_total 3645
telemt_me_idle_close_by_peer_total 3645
telemt_me_route_drop_no_conn_total 1400627
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2253615
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9910
telemt_desync_full_logged_total 3236
telemt_desync_suppressed_total 6674
telemt_desync_frames_bucket_total{bucket="1_2"} 1828
telemt_desync_frames_bucket_total{bucket="3_10"} 3883
telemt_desync_frames_bucket_total{bucket="gt_10"} 4199
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 3550
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3328
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2253499
telemt_user_connections_current{user="hello"} 2489
telemt_user_octets_from_client{user="hello"} 34622122822 (32.24 GB)
telemt_user_octets_to_client{user="hello"} 798209381834 (743.39 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 911
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 30614.8 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2583840
telemt_connections_bad_total 454704
telemt_connections_current 1714
telemt_connections_me_current 1714
telemt_handshake_timeouts_total 30870
telemt_upstream_connect_attempt_total 4722
telemt_upstream_connect_success_total 4687
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4079
telemt_me_reconnect_success_total 3154
telemt_me_reader_eof_total 3269
telemt_me_idle_close_by_peer_total 3268
telemt_me_route_drop_no_conn_total 1833355
telemt_me_route_drop_channel_closed_total 164
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1811810
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6870
telemt_desync_full_logged_total 2056
telemt_desync_suppressed_total 4814
telemt_desync_frames_bucket_total{bucket="1_2"} 1740
telemt_desync_frames_bucket_total{bucket="3_10"} 2587
telemt_desync_frames_bucket_total{bucket="gt_10"} 2543
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 3170
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3153
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1807748
telemt_user_connections_current{user="hello"} 1714
telemt_user_octets_from_client{user="hello"} 25969423688 (24.19 GB)
telemt_user_octets_to_client{user="hello"} 649591037444 (604.98 GB)
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 30602.2 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2261452
telemt_connections_bad_total 91930
telemt_connections_current 1577
telemt_connections_me_current 1577
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 28133
telemt_upstream_connect_attempt_total 34922
telemt_upstream_connect_success_total 33223
telemt_upstream_connect_fail_total 1699
telemt_upstream_connect_attempts_per_request{bucket="1"} 34922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 440
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1699
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6205
telemt_me_reconnect_success_total 3612
telemt_me_reader_eof_total 3743
telemt_me_idle_close_by_peer_total 3742
telemt_me_route_drop_no_conn_total 1795152
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1928245
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7744
telemt_desync_full_logged_total 2413
telemt_desync_suppressed_total 5331
telemt_desync_frames_bucket_total{bucket="1_2"} 1920
telemt_desync_frames_bucket_total{bucket="3_10"} 2812
telemt_desync_frames_bucket_total{bucket="gt_10"} 3012
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 346
telemt_me_writer_removed_unexpected_total 4111
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3608
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 1955197
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 32435126852 (30.21 GB)
telemt_user_octets_to_client{user="hello"} 483447569151 (450.25 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 84325.4 (23h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5933233
telemt_connections_bad_total 1029972
telemt_connections_current 2211
telemt_connections_me_current 2211
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 107894
telemt_upstream_connect_attempt_total 66314
telemt_upstream_connect_success_total 63813
telemt_upstream_connect_fail_total 2501
telemt_upstream_connect_attempts_per_request{bucket="1"} 66314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75843
telemt_me_reconnect_success_total 10427
telemt_me_reader_eof_total 11008
telemt_me_idle_close_by_peer_total 11005
telemt_me_route_drop_no_conn_total 2712953
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4198281
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
telemt_desync_total 18428
telemt_desync_full_logged_total 5726
telemt_desync_suppressed_total 12702
telemt_desync_frames_bucket_total{bucket="1_2"} 3161
telemt_desync_frames_bucket_total{bucket="3_10"} 7629
telemt_desync_frames_bucket_total{bucket="gt_10"} 7638
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 10689
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10403
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 4246332
telemt_user_connections_current{user="hello"} 2211
telemt_user_octets_from_client{user="hello"} 66083961607 (61.55 GB)
telemt_user_octets_to_client{user="hello"} 1630062960456 (1.48 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 804
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 30565.6 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606056
telemt_connections_bad_total 47598
telemt_connections_current 505
telemt_connections_me_current 505
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11630
telemt_upstream_connect_attempt_total 8704
telemt_upstream_connect_success_total 8507
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 553
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4046
telemt_me_reconnect_success_total 3983
telemt_me_reader_eof_total 4138
telemt_me_idle_close_by_peer_total 4137
telemt_me_route_drop_no_conn_total 398072
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 483983
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
telemt_desync_total 1318
telemt_desync_full_logged_total 476
telemt_desync_suppressed_total 842
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 573
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 139
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4018
telemt_me_writer_restored_same_endpoint_total 3974
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 501194
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 6615261768 (6.16 GB)
telemt_user_octets_to_client{user="hello"} 110424731998 (102.84 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 30566.8 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1783036
telemt_connections_bad_total 105071
telemt_connections_current 1920
telemt_connections_me_current 1920
telemt_handshake_timeouts_total 31124
telemt_upstream_connect_attempt_total 5066
telemt_upstream_connect_success_total 5028
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 5066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3519
telemt_me_reconnect_success_total 3485
telemt_me_reader_eof_total 3663
telemt_me_idle_close_by_peer_total 3663
telemt_me_route_drop_no_conn_total 671097
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1549588
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8300
telemt_desync_full_logged_total 2593
telemt_desync_suppressed_total 5707
telemt_desync_frames_bucket_total{bucket="1_2"} 1539
telemt_desync_frames_bucket_total{bucket="3_10"} 2899
telemt_desync_frames_bucket_total{bucket="gt_10"} 3862
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3550
telemt_me_writer_restored_same_endpoint_total 3468
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 1548742
telemt_user_connections_current{user="hello"} 1920
telemt_user_octets_from_client{user="hello"} 26463870228 (24.65 GB)
telemt_user_octets_to_client{user="hello"} 758021821072 (705.96 GB)
telemt_user_unique_ips_current{user="hello"} 686
telemt_user_unique_ips_recent_window{user="hello"} 167
```