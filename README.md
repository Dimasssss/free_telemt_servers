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

# Server Metrics 2026-03-19 23:36:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 22745.9 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469866
telemt_connections_bad_total 29828
telemt_connections_current 773
telemt_connections_me_current 773
telemt_handshake_timeouts_total 7206
telemt_upstream_connect_attempt_total 3808
telemt_upstream_connect_success_total 3777
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 3808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2633
telemt_me_reconnect_success_total 2614
telemt_me_reader_eof_total 2776
telemt_me_idle_close_by_peer_total 2776
telemt_me_route_drop_no_conn_total 139496
telemt_me_route_drop_channel_closed_total 53
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372947
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1956
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 407
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 910
telemt_pool_swap_total 25
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2667
telemt_me_writer_restored_same_endpoint_total 2601
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 373219
telemt_user_connections_current{user="hello"} 773
telemt_user_octets_from_client{user="hello"} 25506402172 (23.75 GB)
telemt_user_octets_to_client{user="hello"} 137342174388 (127.91 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 39201.2 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2877034
telemt_connections_bad_total 122922
telemt_connections_current 1409
telemt_connections_me_current 1409
telemt_handshake_timeouts_total 59307
telemt_upstream_connect_attempt_total 7853
telemt_upstream_connect_success_total 7726
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 7853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8766
telemt_me_reconnect_success_total 4530
telemt_me_reader_eof_total 4858
telemt_me_idle_close_by_peer_total 4858
telemt_me_route_drop_no_conn_total 1468640
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2460337
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10735
telemt_desync_full_logged_total 3546
telemt_desync_suppressed_total 7189
telemt_desync_frames_bucket_total{bucket="1_2"} 2010
telemt_desync_frames_bucket_total{bucket="3_10"} 4212
telemt_desync_frames_bucket_total{bucket="gt_10"} 4513
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 4710
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4475
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 2460165
telemt_user_connections_current{user="hello"} 1409
telemt_user_octets_from_client{user="hello"} 38345110986 (35.71 GB)
telemt_user_octets_to_client{user="hello"} 888839715850 (827.80 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 651
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 39179.3 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2800788
telemt_connections_bad_total 465253
telemt_connections_current 1077
telemt_connections_me_current 1077
telemt_handshake_timeouts_total 37540
telemt_upstream_connect_attempt_total 6212
telemt_upstream_connect_success_total 6164
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5126
telemt_me_reconnect_success_total 4195
telemt_me_reader_eof_total 4380
telemt_me_idle_close_by_peer_total 4379
telemt_me_route_drop_no_conn_total 1887339
telemt_me_route_drop_channel_closed_total 170
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1948525
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7513
telemt_desync_full_logged_total 2270
telemt_desync_suppressed_total 5243
telemt_desync_frames_bucket_total{bucket="1_2"} 1849
telemt_desync_frames_bucket_total{bucket="3_10"} 2859
telemt_desync_frames_bucket_total{bucket="gt_10"} 2805
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4232
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4194
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1944316
telemt_user_connections_current{user="hello"} 1077
telemt_user_octets_from_client{user="hello"} 29185759168 (27.18 GB)
telemt_user_octets_to_client{user="hello"} 739935257988 (689.12 GB)
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 39167.1 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2439441
telemt_connections_bad_total 100206
telemt_connections_current 1061
telemt_connections_me_current 1061
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 29933
telemt_upstream_connect_attempt_total 53179
telemt_upstream_connect_success_total 49020
telemt_upstream_connect_fail_total 4159
telemt_upstream_connect_attempts_per_request{bucket="1"} 53179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6814
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 520
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4159
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7487
telemt_me_reconnect_success_total 4730
telemt_me_reader_eof_total 4898
telemt_me_idle_close_by_peer_total 4897
telemt_me_route_drop_no_conn_total 1841077
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2057321
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8147
telemt_desync_full_logged_total 2570
telemt_desync_suppressed_total 5577
telemt_desync_frames_bucket_total{bucket="1_2"} 1998
telemt_desync_frames_bucket_total{bucket="3_10"} 2961
telemt_desync_frames_bucket_total{bucket="gt_10"} 3188
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5301
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4726
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 571
telemt_user_connections_total{user="hello"} 2098477
telemt_user_connections_current{user="hello"} 1061
telemt_user_octets_from_client{user="hello"} 34372203311 (32.01 GB)
telemt_user_octets_to_client{user="hello"} 569940556519 (530.80 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 92890.6 (25h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6152780
telemt_connections_bad_total 1037569
telemt_connections_current 1274
telemt_connections_me_current 1274
telemt_relay_adaptive_promotions_total 27
telemt_relay_adaptive_demotions_total 3535
telemt_relay_adaptive_hard_promotions_total 25
telemt_handshake_timeouts_total 110654
telemt_upstream_connect_attempt_total 116891
telemt_upstream_connect_success_total 85564
telemt_upstream_connect_fail_total 31327
telemt_upstream_connect_attempts_per_request{bucket="1"} 116891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31327
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77434
telemt_me_reconnect_success_total 11897
telemt_me_reader_eof_total 12690
telemt_me_idle_close_by_peer_total 12679
telemt_me_route_drop_no_conn_total 2767457
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4348498
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
telemt_desync_total 19135
telemt_desync_full_logged_total 6004
telemt_desync_suppressed_total 13131
telemt_desync_frames_bucket_total{bucket="1_2"} 3346
telemt_desync_frames_bucket_total{bucket="3_10"} 7850
telemt_desync_frames_bucket_total{bucket="gt_10"} 7939
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 12185
telemt_me_refill_failed_total 2043
telemt_me_writer_restored_same_endpoint_total 11872
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 4416407
telemt_user_connections_current{user="hello"} 1274
telemt_user_octets_from_client{user="hello"} 68196769674 (63.51 GB)
telemt_user_octets_to_client{user="hello"} 1709940732932 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 702760
telemt_user_msgs_to_client{user="hello"} 2862853
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 39130.3 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673689
telemt_connections_bad_total 67836
telemt_connections_current 295
telemt_connections_me_current 295
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12832
telemt_upstream_connect_attempt_total 12035
telemt_upstream_connect_success_total 11705
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 660
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5388
telemt_me_reconnect_success_total 5284
telemt_me_reader_eof_total 5509
telemt_me_idle_close_by_peer_total 5506
telemt_me_route_drop_no_conn_total 455784
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 555945
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
telemt_desync_total 1385
telemt_desync_full_logged_total 517
telemt_desync_suppressed_total 868
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 571
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5330
telemt_me_writer_restored_same_endpoint_total 5275
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 544089
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 7075352479 (6.59 GB)
telemt_user_octets_to_client{user="hello"} 132846918510 (123.72 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 39131.6 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1943082
telemt_connections_bad_total 117249
telemt_connections_current 1185
telemt_connections_me_current 1185
telemt_handshake_timeouts_total 36058
telemt_upstream_connect_attempt_total 6795
telemt_upstream_connect_success_total 6743
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 6795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3097
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4804
telemt_me_reconnect_success_total 4767
telemt_me_reader_eof_total 5028
telemt_me_idle_close_by_peer_total 5028
telemt_me_route_drop_no_conn_total 719852
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1672507
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8896
telemt_desync_full_logged_total 2839
telemt_desync_suppressed_total 6057
telemt_desync_frames_bucket_total{bucket="1_2"} 1630
telemt_desync_frames_bucket_total{bucket="3_10"} 3122
telemt_desync_frames_bucket_total{bucket="gt_10"} 4144
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4845
telemt_me_writer_restored_same_endpoint_total 4750
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1671643
telemt_user_connections_current{user="hello"} 1185
telemt_user_octets_from_client{user="hello"} 28328145348 (26.38 GB)
telemt_user_octets_to_client{user="hello"} 846453009740 (788.32 GB)
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 88
```