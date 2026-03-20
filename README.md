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

# Server Metrics 2026-03-20 04:02:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 38665.5 (10h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712203
telemt_connections_bad_total 49678
telemt_connections_current 1148
telemt_connections_me_current 1148
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15672
telemt_upstream_connect_attempt_total 7781
telemt_upstream_connect_success_total 7687
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 7781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4700
telemt_me_reconnect_success_total 4660
telemt_me_reader_eof_total 4930
telemt_me_idle_close_by_peer_total 4929
telemt_me_route_drop_no_conn_total 201402
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 565245
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2804
telemt_desync_full_logged_total 1024
telemt_desync_suppressed_total 1780
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 1051
telemt_desync_frames_bucket_total{bucket="gt_10"} 1198
telemt_pool_swap_total 42
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4703
telemt_me_writer_restored_same_endpoint_total 4647
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 566631
telemt_user_connections_current{user="hello"} 1148
telemt_user_octets_from_client{user="hello"} 31503781308 (29.34 GB)
telemt_user_octets_to_client{user="hello"} 194160482545 (180.83 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 55120.9 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3337761
telemt_connections_bad_total 229859
telemt_connections_current 2478
telemt_connections_me_current 2478
telemt_handshake_timeouts_total 71922
telemt_upstream_connect_attempt_total 10648
telemt_upstream_connect_success_total 10457
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 10648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10724
telemt_me_reconnect_success_total 6475
telemt_me_reader_eof_total 6929
telemt_me_idle_close_by_peer_total 6929
telemt_me_route_drop_no_conn_total 1569995
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2791206
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11722
telemt_desync_full_logged_total 3887
telemt_desync_suppressed_total 7835
telemt_desync_frames_bucket_total{bucket="1_2"} 2252
telemt_desync_frames_bucket_total{bucket="3_10"} 4572
telemt_desync_frames_bucket_total{bucket="gt_10"} 4898
telemt_pool_swap_total 49
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6685
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6420
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 2790910
telemt_user_connections_current{user="hello"} 2478
telemt_user_octets_from_client{user="hello"} 42615330306 (39.69 GB)
telemt_user_octets_to_client{user="hello"} 1049578856990 (977.50 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 346
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 55098.9 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3143815
telemt_connections_bad_total 483789
telemt_connections_current 1988
telemt_connections_me_current 1988
telemt_handshake_timeouts_total 50049
telemt_upstream_connect_attempt_total 9024
telemt_upstream_connect_success_total 8959
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7143
telemt_me_reconnect_success_total 6206
telemt_me_reader_eof_total 6531
telemt_me_idle_close_by_peer_total 6530
telemt_me_route_drop_no_conn_total 1983152
telemt_me_route_drop_channel_closed_total 176
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2187229
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8058
telemt_desync_full_logged_total 2480
telemt_desync_suppressed_total 5578
telemt_desync_frames_bucket_total{bucket="1_2"} 1981
telemt_desync_frames_bucket_total{bucket="3_10"} 3060
telemt_desync_frames_bucket_total{bucket="gt_10"} 3017
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 6268
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6205
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 2182252
telemt_user_connections_current{user="hello"} 1988
telemt_user_octets_from_client{user="hello"} 33111880720 (30.84 GB)
telemt_user_octets_to_client{user="hello"} 856986264828 (798.13 GB)
telemt_user_unique_ips_current{user="hello"} 744
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 55086.7 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2837525
telemt_connections_bad_total 219433
telemt_connections_current 1921
telemt_connections_me_current 1921
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 34091
telemt_upstream_connect_attempt_total 61536
telemt_upstream_connect_success_total 57035
telemt_upstream_connect_fail_total 4501
telemt_upstream_connect_attempts_per_request{bucket="1"} 61536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 550
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4501
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9466
telemt_me_reconnect_success_total 6548
telemt_me_reader_eof_total 6829
telemt_me_idle_close_by_peer_total 6828
telemt_me_route_drop_no_conn_total 1937902
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2293688
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8852
telemt_desync_full_logged_total 2826
telemt_desync_suppressed_total 6026
telemt_desync_frames_bucket_total{bucket="1_2"} 2157
telemt_desync_frames_bucket_total{bucket="3_10"} 3229
telemt_desync_frames_bucket_total{bucket="gt_10"} 3466
telemt_pool_swap_total 42
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7225
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6544
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 677
telemt_user_connections_total{user="hello"} 2339828
telemt_user_connections_current{user="hello"} 1921
telemt_user_octets_from_client{user="hello"} 37241287178 (34.68 GB)
telemt_user_octets_to_client{user="hello"} 687939343227 (640.69 GB)
telemt_user_msgs_from_client{user="hello"} 251914
telemt_user_msgs_to_client{user="hello"} 1773933
telemt_user_unique_ips_current{user="hello"} 705
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 108810.0 (30h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6559193
telemt_connections_bad_total 1147333
telemt_connections_current 1994
telemt_connections_me_current 1994
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 117213
telemt_upstream_connect_attempt_total 128959
telemt_upstream_connect_success_total 95667
telemt_upstream_connect_fail_total 33292
telemt_upstream_connect_attempts_per_request{bucket="1"} 128959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33292
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79624
telemt_me_reconnect_success_total 13949
telemt_me_reader_eof_total 15007
telemt_me_idle_close_by_peer_total 14993
telemt_me_route_drop_no_conn_total 2855063
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4616444
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
telemt_desync_total 20053
telemt_desync_full_logged_total 6379
telemt_desync_suppressed_total 13674
telemt_desync_frames_bucket_total{bucket="1_2"} 3542
telemt_desync_frames_bucket_total{bucket="3_10"} 8292
telemt_desync_frames_bucket_total{bucket="gt_10"} 8219
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 14267
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13924
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 4691514
telemt_user_connections_current{user="hello"} 1994
telemt_user_octets_from_client{user="hello"} 74482971560 (69.37 GB)
telemt_user_octets_to_client{user="hello"} 1829486070740 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 811
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 55050.0 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1211318
telemt_connections_bad_total 94560
telemt_connections_current 774
telemt_connections_me_current 774
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13614
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
telemt_me_route_drop_no_conn_total 473188
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
telemt_desync_total 1432
telemt_desync_full_logged_total 547
telemt_desync_suppressed_total 885
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 603
telemt_desync_frames_bucket_total{bucket="gt_10"} 608
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
telemt_user_connections_total{user="hello"} 1047726
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 8108293383 (7.55 GB)
telemt_user_octets_to_client{user="hello"} 146607291434 (136.54 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 55051.4 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2201367
telemt_connections_bad_total 136422
telemt_connections_current 2045
telemt_connections_me_current 2045
telemt_handshake_timeouts_total 41805
telemt_upstream_connect_attempt_total 9950
telemt_upstream_connect_success_total 9885
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7168
telemt_me_reconnect_success_total 7120
telemt_me_reader_eof_total 7520
telemt_me_idle_close_by_peer_total 7520
telemt_me_route_drop_no_conn_total 786274
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1868545
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9616
telemt_desync_full_logged_total 3096
telemt_desync_suppressed_total 6520
telemt_desync_frames_bucket_total{bucket="1_2"} 1870
telemt_desync_frames_bucket_total{bucket="3_10"} 3375
telemt_desync_frames_bucket_total{bucket="gt_10"} 4371
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 7219
telemt_me_writer_restored_same_endpoint_total 7103
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 1867645
telemt_user_connections_current{user="hello"} 2045
telemt_user_octets_from_client{user="hello"} 37255189724 (34.70 GB)
telemt_user_octets_to_client{user="hello"} 969018892212 (902.47 GB)
telemt_user_unique_ips_current{user="hello"} 742
telemt_user_unique_ips_recent_window{user="hello"} 241
```