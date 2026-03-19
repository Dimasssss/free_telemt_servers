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

# Server Metrics 2026-03-19 18:53:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 5733.1 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184677
telemt_connections_bad_total 6672
telemt_connections_current 1367
telemt_connections_me_current 1367
telemt_handshake_timeouts_total 1966
telemt_upstream_connect_attempt_total 866
telemt_upstream_connect_success_total 853
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 528
telemt_me_reconnect_success_total 525
telemt_me_reader_eof_total 541
telemt_me_idle_close_by_peer_total 541
telemt_me_route_drop_no_conn_total 57340
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146921
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 664
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 447
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_restored_same_endpoint_total 512
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 147123
telemt_user_connections_current{user="hello"} 1367
telemt_user_octets_from_client{user="hello"} 2261241600 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 48990790596 (45.63 GB)
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 22188.5 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2159656
telemt_connections_bad_total 100675
telemt_connections_current 3542
telemt_connections_me_current 3542
telemt_handshake_timeouts_total 40494
telemt_upstream_connect_attempt_total 4977
telemt_upstream_connect_success_total 4911
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6769
telemt_me_reconnect_success_total 2544
telemt_me_reader_eof_total 2743
telemt_me_idle_close_by_peer_total 2743
telemt_me_route_drop_no_conn_total 1210421
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1809654
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7422
telemt_desync_full_logged_total 2359
telemt_desync_suppressed_total 5063
telemt_desync_frames_bucket_total{bucket="1_2"} 1397
telemt_desync_frames_bucket_total{bucket="3_10"} 2931
telemt_desync_frames_bucket_total{bucket="gt_10"} 3094
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2690
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2489
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1809600
telemt_user_connections_current{user="hello"} 3542
telemt_user_octets_from_client{user="hello"} 26229280802 (24.43 GB)
telemt_user_octets_to_client{user="hello"} 598016999986 (556.95 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1249
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 22166.9 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1966174
telemt_connections_bad_total 230967
telemt_connections_current 2830
telemt_connections_me_current 2830
telemt_handshake_timeouts_total 22683
telemt_upstream_connect_attempt_total 3475
telemt_upstream_connect_success_total 3450
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3229
telemt_me_reconnect_success_total 2311
telemt_me_reader_eof_total 2364
telemt_me_idle_close_by_peer_total 2363
telemt_me_route_drop_no_conn_total 1709785
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1499325
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5098
telemt_desync_full_logged_total 1517
telemt_desync_suppressed_total 3581
telemt_desync_frames_bucket_total{bucket="1_2"} 1301
telemt_desync_frames_bucket_total{bucket="3_10"} 1918
telemt_desync_frames_bucket_total{bucket="gt_10"} 1879
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 2307
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2310
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1495684
telemt_user_connections_current{user="hello"} 2830
telemt_user_octets_from_client{user="hello"} 19776968360 (18.42 GB)
telemt_user_octets_to_client{user="hello"} 487440405844 (453.96 GB)
telemt_user_unique_ips_current{user="hello"} 951
telemt_user_unique_ips_recent_window{user="hello"} 353
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 22154.4 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1842716
telemt_connections_bad_total 61491
telemt_connections_current 2537
telemt_connections_me_current 2537
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 24508
telemt_upstream_connect_attempt_total 25502
telemt_upstream_connect_success_total 24309
telemt_upstream_connect_fail_total 1193
telemt_upstream_connect_attempts_per_request{bucket="1"} 25502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1193
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5126
telemt_me_reconnect_success_total 2744
telemt_me_reader_eof_total 2840
telemt_me_idle_close_by_peer_total 2839
telemt_me_route_drop_no_conn_total 1599009
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1590159
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6268
telemt_desync_full_logged_total 1943
telemt_desync_suppressed_total 4325
telemt_desync_frames_bucket_total{bucket="1_2"} 1627
telemt_desync_frames_bucket_total{bucket="3_10"} 2301
telemt_desync_frames_bucket_total{bucket="gt_10"} 2340
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 3159
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2740
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 415
telemt_user_connections_total{user="hello"} 1609497
telemt_user_connections_current{user="hello"} 2537
telemt_user_octets_from_client{user="hello"} 27561967073 (25.67 GB)
telemt_user_octets_to_client{user="hello"} 356692839109 (332.20 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 906
telemt_user_unique_ips_recent_window{user="hello"} 346
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 75877.7 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5534851
telemt_connections_bad_total 1008001
telemt_connections_current 3150
telemt_connections_me_current 3150
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 101003
telemt_upstream_connect_attempt_total 65086
telemt_upstream_connect_success_total 62592
telemt_upstream_connect_fail_total 2494
telemt_upstream_connect_attempts_per_request{bucket="1"} 65086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1050
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2494
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75010
telemt_me_reconnect_success_total 9600
telemt_me_reader_eof_total 10121
telemt_me_idle_close_by_peer_total 10118
telemt_me_route_drop_no_conn_total 2541210
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3851275
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
telemt_desync_total 16954
telemt_desync_full_logged_total 5195
telemt_desync_suppressed_total 11759
telemt_desync_frames_bucket_total{bucket="1_2"} 2817
telemt_desync_frames_bucket_total{bucket="3_10"} 7047
telemt_desync_frames_bucket_total{bucket="gt_10"} 7090
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 9847
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9576
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 3899403
telemt_user_connections_current{user="hello"} 3150
telemt_user_octets_from_client{user="hello"} 61138184611 (56.94 GB)
telemt_user_octets_to_client{user="hello"} 1436675289100 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1128
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 22118.1 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510882
telemt_connections_bad_total 35782
telemt_connections_current 643
telemt_connections_me_current 643
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10399
telemt_upstream_connect_attempt_total 7285
telemt_upstream_connect_success_total 7088
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 3015
telemt_me_reconnect_success_total 2958
telemt_me_reader_eof_total 3041
telemt_me_idle_close_by_peer_total 3040
telemt_me_route_drop_no_conn_total 361138
telemt_me_route_drop_channel_closed_total 126
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404780
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
telemt_desync_total 1080
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 736
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 441
telemt_desync_frames_bucket_total{bucket="gt_10"} 464
telemt_pool_swap_total 14
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 132
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2980
telemt_me_writer_restored_same_endpoint_total 2949
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 423426
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 4832349908 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 88671682486 (82.58 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 22119.1 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1439561
telemt_connections_bad_total 88913
telemt_connections_current 3001
telemt_connections_me_current 3001
telemt_handshake_timeouts_total 24933
telemt_upstream_connect_attempt_total 3646
telemt_upstream_connect_success_total 3619
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 2501
telemt_me_reconnect_success_total 2474
telemt_me_reader_eof_total 2595
telemt_me_idle_close_by_peer_total 2595
telemt_me_route_drop_no_conn_total 552636
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1247177
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6599
telemt_desync_full_logged_total 2034
telemt_desync_suppressed_total 4565
telemt_desync_frames_bucket_total{bucket="1_2"} 1257
telemt_desync_frames_bucket_total{bucket="3_10"} 2306
telemt_desync_frames_bucket_total{bucket="gt_10"} 3036
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 2525
telemt_me_writer_restored_same_endpoint_total 2457
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1246469
telemt_user_connections_current{user="hello"} 3001
telemt_user_octets_from_client{user="hello"} 19799665476 (18.44 GB)
telemt_user_octets_to_client{user="hello"} 553934963316 (515.89 GB)
telemt_user_unique_ips_current{user="hello"} 963
telemt_user_unique_ips_recent_window{user="hello"} 343
```