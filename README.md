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

# Server Metrics 2026-03-19 23:46:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 23357.6 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476785
telemt_connections_bad_total 30368
telemt_connections_current 765
telemt_connections_me_current 765
telemt_handshake_timeouts_total 7293
telemt_upstream_connect_attempt_total 3887
telemt_upstream_connect_success_total 3856
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 3887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2712
telemt_me_reconnect_success_total 2693
telemt_me_reader_eof_total 2857
telemt_me_idle_close_by_peer_total 2857
telemt_me_route_drop_no_conn_total 141219
telemt_me_route_drop_channel_closed_total 54
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378329
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1971
telemt_desync_full_logged_total 695
telemt_desync_suppressed_total 1276
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 916
telemt_pool_swap_total 25
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2748
telemt_me_writer_restored_same_endpoint_total 2680
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 378603
telemt_user_connections_current{user="hello"} 765
telemt_user_octets_from_client{user="hello"} 27499569184 (25.61 GB)
telemt_user_octets_to_client{user="hello"} 140063855868 (130.44 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 39812.7 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2887598
telemt_connections_bad_total 123194
telemt_connections_current 1328
telemt_connections_me_current 1328
telemt_handshake_timeouts_total 60057
telemt_upstream_connect_attempt_total 7974
telemt_upstream_connect_success_total 7843
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 7974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8840
telemt_me_reconnect_success_total 4604
telemt_me_reader_eof_total 4939
telemt_me_idle_close_by_peer_total 4939
telemt_me_route_drop_no_conn_total 1471575
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2469578
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10745
telemt_desync_full_logged_total 3551
telemt_desync_suppressed_total 7194
telemt_desync_frames_bucket_total{bucket="1_2"} 2011
telemt_desync_frames_bucket_total{bucket="3_10"} 4217
telemt_desync_frames_bucket_total{bucket="gt_10"} 4517
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 4786
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4549
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 2469402
telemt_user_connections_current{user="hello"} 1328
telemt_user_octets_from_client{user="hello"} 38418816062 (35.78 GB)
telemt_user_octets_to_client{user="hello"} 893043277038 (831.71 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 609
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 39790.6 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2813873
telemt_connections_bad_total 466962
telemt_connections_current 1042
telemt_connections_me_current 1042
telemt_handshake_timeouts_total 37930
telemt_upstream_connect_attempt_total 6335
telemt_upstream_connect_success_total 6287
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5206
telemt_me_reconnect_success_total 4275
telemt_me_reader_eof_total 4469
telemt_me_idle_close_by_peer_total 4468
telemt_me_route_drop_no_conn_total 1889684
telemt_me_route_drop_channel_closed_total 170
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1955770
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7514
telemt_desync_full_logged_total 2271
telemt_desync_suppressed_total 5243
telemt_desync_frames_bucket_total{bucket="1_2"} 1849
telemt_desync_frames_bucket_total{bucket="3_10"} 2859
telemt_desync_frames_bucket_total{bucket="gt_10"} 2806
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4314
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4274
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1951549
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 29256020208 (27.25 GB)
telemt_user_octets_to_client{user="hello"} 742343030704 (691.36 GB)
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 39778.7 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2450343
telemt_connections_bad_total 102378
telemt_connections_current 1054
telemt_connections_me_current 1054
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30082
telemt_upstream_connect_attempt_total 53309
telemt_upstream_connect_success_total 49146
telemt_upstream_connect_fail_total 4163
telemt_upstream_connect_attempts_per_request{bucket="1"} 53309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 520
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4163
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7574
telemt_me_reconnect_success_total 4813
telemt_me_reader_eof_total 4990
telemt_me_idle_close_by_peer_total 4989
telemt_me_route_drop_no_conn_total 1842857
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2064576
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8161
telemt_desync_full_logged_total 2575
telemt_desync_suppressed_total 5586
telemt_desync_frames_bucket_total{bucket="1_2"} 2002
telemt_desync_frames_bucket_total{bucket="3_10"} 2968
telemt_desync_frames_bucket_total{bucket="gt_10"} 3191
telemt_pool_swap_total 25
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5385
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4809
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 2105732
telemt_user_connections_current{user="hello"} 1054
telemt_user_octets_from_client{user="hello"} 34493246235 (32.12 GB)
telemt_user_octets_to_client{user="hello"} 573154920843 (533.79 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 93502.0 (25h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6162408
telemt_connections_bad_total 1037874
telemt_connections_current 1205
telemt_connections_me_current 1205
telemt_relay_adaptive_promotions_total 27
telemt_relay_adaptive_demotions_total 3535
telemt_relay_adaptive_hard_promotions_total 25
telemt_handshake_timeouts_total 110787
telemt_upstream_connect_attempt_total 116972
telemt_upstream_connect_success_total 85645
telemt_upstream_connect_fail_total 31327
telemt_upstream_connect_attempts_per_request{bucket="1"} 116972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31327
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77515
telemt_me_reconnect_success_total 11978
telemt_me_reader_eof_total 12773
telemt_me_idle_close_by_peer_total 12762
telemt_me_route_drop_no_conn_total 2769792
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4357385
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
telemt_desync_total 19163
telemt_desync_full_logged_total 6021
telemt_desync_suppressed_total 13142
telemt_desync_frames_bucket_total{bucket="1_2"} 3348
telemt_desync_frames_bucket_total{bucket="3_10"} 7863
telemt_desync_frames_bucket_total{bucket="gt_10"} 7952
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 12268
telemt_me_refill_failed_total 2043
telemt_me_writer_restored_same_endpoint_total 11953
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 4425294
telemt_user_connections_current{user="hello"} 1205
telemt_user_octets_from_client{user="hello"} 68259099514 (63.57 GB)
telemt_user_octets_to_client{user="hello"} 1712333556508 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 702760
telemt_user_msgs_to_client{user="hello"} 2862853
telemt_user_unique_ips_current{user="hello"} 507
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 39741.8 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 676336
telemt_connections_bad_total 68444
telemt_connections_current 307
telemt_connections_me_current 307
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12839
telemt_upstream_connect_attempt_total 12178
telemt_upstream_connect_success_total 11848
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6122
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 660
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5488
telemt_me_reconnect_success_total 5384
telemt_me_reader_eof_total 5617
telemt_me_idle_close_by_peer_total 5614
telemt_me_route_drop_no_conn_total 456874
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557874
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
telemt_desync_total 1388
telemt_desync_full_logged_total 520
telemt_desync_suppressed_total 868
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 573
telemt_desync_frames_bucket_total{bucket="gt_10"} 597
telemt_pool_swap_total 34
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5431
telemt_me_writer_restored_same_endpoint_total 5375
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 546018
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 7087967371 (6.60 GB)
telemt_user_octets_to_client{user="hello"} 133181806662 (124.04 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 39743.2 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1949502
telemt_connections_bad_total 117252
telemt_connections_current 1219
telemt_connections_me_current 1219
telemt_handshake_timeouts_total 36171
telemt_upstream_connect_attempt_total 6920
telemt_upstream_connect_success_total 6866
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 6919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4884
telemt_me_reconnect_success_total 4846
telemt_me_reader_eof_total 5115
telemt_me_idle_close_by_peer_total 5115
telemt_me_route_drop_no_conn_total 722448
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1678313
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8935
telemt_desync_full_logged_total 2853
telemt_desync_suppressed_total 6082
telemt_desync_frames_bucket_total{bucket="1_2"} 1637
telemt_desync_frames_bucket_total{bucket="3_10"} 3143
telemt_desync_frames_bucket_total{bucket="gt_10"} 4155
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 4925
telemt_me_writer_restored_same_endpoint_total 4829
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 1677450
telemt_user_connections_current{user="hello"} 1219
telemt_user_octets_from_client{user="hello"} 28399095332 (26.45 GB)
telemt_user_octets_to_client{user="hello"} 850080157924 (791.70 GB)
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 97
```