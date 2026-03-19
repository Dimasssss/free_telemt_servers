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

# Server Metrics 2026-03-19 16:45:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 9652.5 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361963
telemt_connections_bad_total 10111
telemt_connections_current 1721
telemt_connections_direct_current 1721
telemt_relay_adaptive_promotions_total 100
telemt_relay_adaptive_demotions_total 30223
telemt_relay_adaptive_hard_promotions_total 99
telemt_handshake_timeouts_total 3957
telemt_upstream_connect_attempt_total 315197
telemt_upstream_connect_success_total 315042
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 315197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 301172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 315040
telemt_user_connections_current{user="hello"} 1721
telemt_user_octets_from_client{user="hello"} 7881177572 (7.34 GB)
telemt_user_octets_to_client{user="hello"} 66836302156 (62.25 GB)
telemt_user_msgs_from_client{user="hello"} 6605345
telemt_user_msgs_to_client{user="hello"} 6613238
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 270
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 14527.8 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1544448
telemt_connections_bad_total 85180
telemt_connections_current 3824
telemt_connections_me_current 3824
telemt_handshake_timeouts_total 29121
telemt_upstream_connect_attempt_total 3821
telemt_upstream_connect_success_total 3777
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 3821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 5982
telemt_me_reconnect_success_total 1762
telemt_me_reader_eof_total 1910
telemt_me_idle_close_by_peer_total 1910
telemt_me_route_drop_no_conn_total 952715
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1251689
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4684
telemt_desync_full_logged_total 1442
telemt_desync_suppressed_total 3242
telemt_desync_frames_bucket_total{bucket="1_2"} 937
telemt_desync_frames_bucket_total{bucket="3_10"} 1835
telemt_desync_frames_bucket_total{bucket="gt_10"} 1912
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1900
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1707
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 1251831
telemt_user_connections_current{user="hello"} 3824
telemt_user_octets_from_client{user="hello"} 16939310126 (15.78 GB)
telemt_user_octets_to_client{user="hello"} 385982839378 (359.47 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1323
telemt_user_unique_ips_recent_window{user="hello"} 589
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 14506.2 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1425553
telemt_connections_bad_total 158427
telemt_connections_current 3033
telemt_connections_me_current 3033
telemt_handshake_timeouts_total 14332
telemt_upstream_connect_attempt_total 2404
telemt_upstream_connect_success_total 2388
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2513
telemt_me_reconnect_success_total 1598
telemt_me_reader_eof_total 1603
telemt_me_idle_close_by_peer_total 1602
telemt_me_route_drop_no_conn_total 1455717
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1095164
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3458
telemt_desync_full_logged_total 988
telemt_desync_suppressed_total 2470
telemt_desync_frames_bucket_total{bucket="1_2"} 936
telemt_desync_frames_bucket_total{bucket="3_10"} 1294
telemt_desync_frames_bucket_total{bucket="gt_10"} 1228
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 1581
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1597
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1092350
telemt_user_connections_current{user="hello"} 3033
telemt_user_octets_from_client{user="hello"} 12856711560 (11.97 GB)
telemt_user_octets_to_client{user="hello"} 305306337408 (284.34 GB)
telemt_user_unique_ips_current{user="hello"} 1021
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 14493.8 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1230315
telemt_connections_bad_total 54113
telemt_connections_current 3037
telemt_connections_me_current 3037
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 18941
telemt_upstream_connect_attempt_total 19345
telemt_upstream_connect_success_total 18453
telemt_upstream_connect_fail_total 892
telemt_upstream_connect_attempts_per_request{bucket="1"} 19345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 333
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 892
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 3126
telemt_me_reconnect_success_total 1741
telemt_me_reader_eof_total 1772
telemt_me_idle_close_by_peer_total 1771
telemt_me_route_drop_no_conn_total 973151
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1050386
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4473
telemt_desync_full_logged_total 1387
telemt_desync_suppressed_total 3086
telemt_desync_frames_bucket_total{bucket="1_2"} 1182
telemt_desync_frames_bucket_total{bucket="3_10"} 1654
telemt_desync_frames_bucket_total{bucket="gt_10"} 1637
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 148
telemt_me_writer_removed_unexpected_total 2028
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 1737
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 1065742
telemt_user_connections_current{user="hello"} 3037
telemt_user_octets_from_client{user="hello"} 21283990373 (19.82 GB)
telemt_user_octets_to_client{user="hello"} 231629832346 (215.72 GB)
telemt_user_msgs_from_client{user="hello"} 40382
telemt_user_msgs_to_client{user="hello"} 85113
telemt_user_unique_ips_current{user="hello"} 963
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 68216.9 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4862839
telemt_connections_bad_total 838511
telemt_connections_current 3362
telemt_connections_me_current 3362
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 94126
telemt_upstream_connect_attempt_total 64035
telemt_upstream_connect_success_total 61544
telemt_upstream_connect_fail_total 2491
telemt_upstream_connect_attempts_per_request{bucket="1"} 64035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1035
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74352
telemt_me_reconnect_success_total 8949
telemt_me_reader_eof_total 9416
telemt_me_idle_close_by_peer_total 9413
telemt_me_route_drop_no_conn_total 2314419
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3403406
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
telemt_desync_total 14872
telemt_desync_full_logged_total 4521
telemt_desync_suppressed_total 10351
telemt_desync_frames_bucket_total{bucket="1_2"} 2468
telemt_desync_frames_bucket_total{bucket="3_10"} 6294
telemt_desync_frames_bucket_total{bucket="gt_10"} 6110
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9180
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 8925
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 3451605
telemt_user_connections_current{user="hello"} 3362
telemt_user_octets_from_client{user="hello"} 53899632063 (50.20 GB)
telemt_user_octets_to_client{user="hello"} 1242908999440 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1152
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 14458.6 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311194
telemt_connections_bad_total 25468
telemt_connections_current 861
telemt_connections_me_current 861
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 7287
telemt_upstream_connect_attempt_total 5398
telemt_upstream_connect_success_total 5261
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 5398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3178
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1994
telemt_me_reconnect_success_total 1957
telemt_me_reader_eof_total 1983
telemt_me_idle_close_by_peer_total 1983
telemt_me_route_drop_no_conn_total 184986
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260118
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
telemt_desync_total 800
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 9
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 1942
telemt_me_writer_restored_same_endpoint_total 1948
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 262700
telemt_user_connections_current{user="hello"} 861
telemt_user_octets_from_client{user="hello"} 3770094656 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 70167355258 (65.35 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 14458.2 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 974918
telemt_connections_bad_total 63219
telemt_connections_current 3039
telemt_connections_me_current 3039
telemt_handshake_timeouts_total 16398
telemt_upstream_connect_attempt_total 2482
telemt_upstream_connect_success_total 2462
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 2482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1710
telemt_me_reconnect_success_total 1688
telemt_me_reader_eof_total 1751
telemt_me_idle_close_by_peer_total 1751
telemt_me_route_drop_no_conn_total 401316
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 838172
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4653
telemt_desync_full_logged_total 1414
telemt_desync_suppressed_total 3239
telemt_desync_frames_bucket_total{bucket="1_2"} 942
telemt_desync_frames_bucket_total{bucket="3_10"} 1594
telemt_desync_frames_bucket_total{bucket="gt_10"} 2117
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 1723
telemt_me_writer_restored_same_endpoint_total 1671
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 837722
telemt_user_connections_current{user="hello"} 3039
telemt_user_octets_from_client{user="hello"} 12675590228 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 363234504148 (338.29 GB)
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 409
```