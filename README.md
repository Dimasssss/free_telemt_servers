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

# Server Metrics 2026-03-18 21:26:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21696.3 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499325
telemt_connections_bad_total 28752
telemt_handshake_timeouts_total 9750
telemt_upstream_connect_attempt_total 3922
telemt_upstream_connect_success_total 3919
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 2814
telemt_me_reconnect_success_total 2797
telemt_me_reader_eof_total 2914
telemt_me_idle_close_by_peer_total 2914
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 201595
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424399
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2573
telemt_desync_full_logged_total 767
telemt_desync_suppressed_total 1806
telemt_desync_frames_bucket_total{bucket="1_2"} 591
telemt_desync_frames_bucket_total{bucket="3_10"} 822
telemt_desync_frames_bucket_total{bucket="gt_10"} 1160
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2849
telemt_me_writer_restored_same_endpoint_total 2777
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 424219
telemt_user_connections_current{user="hello"} 811
telemt_user_octets_from_client{user="hello"} 8197134736 (7.63 GB)
telemt_user_octets_to_client{user="hello"} 157757652956 (146.92 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 26524.2 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2243490
telemt_connections_bad_total 157508
telemt_connections_current 2468
telemt_connections_me_current 2468
telemt_handshake_timeouts_total 37169
telemt_upstream_connect_attempt_total 4125
telemt_upstream_connect_success_total 4098
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2774
telemt_me_reconnect_success_total 2754
telemt_me_reader_eof_total 2812
telemt_me_idle_close_by_peer_total 2811
telemt_me_route_drop_no_conn_total 1872475
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1941117
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7013
telemt_desync_full_logged_total 2285
telemt_desync_suppressed_total 4728
telemt_desync_frames_bucket_total{bucket="1_2"} 1221
telemt_desync_frames_bucket_total{bucket="3_10"} 2751
telemt_desync_frames_bucket_total{bucket="gt_10"} 3041
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2725
telemt_me_writer_restored_same_endpoint_total 2752
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1936508
telemt_user_connections_current{user="hello"} 2468
telemt_user_octets_from_client{user="hello"} 31925130456 (29.73 GB)
telemt_user_octets_to_client{user="hello"} 685885077024 (638.78 GB)
telemt_user_unique_ips_current{user="hello"} 853
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 26454.8 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1722133
telemt_connections_bad_total 142567
telemt_connections_current 2089
telemt_connections_me_current 2089
telemt_handshake_timeouts_total 41144
telemt_upstream_connect_attempt_total 3847
telemt_upstream_connect_success_total 3826
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2500
telemt_me_reconnect_success_total 2479
telemt_me_reader_eof_total 2636
telemt_me_idle_close_by_peer_total 2636
telemt_me_route_drop_no_conn_total 693704
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1390374
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6740
telemt_desync_full_logged_total 2055
telemt_desync_suppressed_total 4685
telemt_desync_frames_bucket_total{bucket="1_2"} 1660
telemt_desync_frames_bucket_total{bucket="3_10"} 2522
telemt_desync_frames_bucket_total{bucket="gt_10"} 2558
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 2537
telemt_me_writer_restored_same_endpoint_total 2462
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1389571
telemt_user_connections_current{user="hello"} 2089
telemt_user_octets_from_client{user="hello"} 29836843220 (27.79 GB)
telemt_user_octets_to_client{user="hello"} 712306208748 (663.39 GB)
telemt_user_unique_ips_current{user="hello"} 726
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 27167.4 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2370068
telemt_connections_bad_total 93260
telemt_connections_current 1619
telemt_connections_me_current 1619
telemt_handshake_timeouts_total 23159
telemt_upstream_connect_attempt_total 4135
telemt_upstream_connect_success_total 4094
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 4135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2725
telemt_me_reconnect_success_total 2695
telemt_me_reader_eof_total 2818
telemt_me_idle_close_by_peer_total 2817
telemt_me_route_drop_no_conn_total 3755251
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2075830
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7921
telemt_desync_full_logged_total 2085
telemt_desync_suppressed_total 5836
telemt_desync_frames_bucket_total{bucket="1_2"} 1743
telemt_desync_frames_bucket_total{bucket="3_10"} 3599
telemt_desync_frames_bucket_total{bucket="gt_10"} 2579
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 2718
telemt_me_writer_restored_same_endpoint_total 2684
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 2075731
telemt_user_connections_current{user="hello"} 1619
telemt_user_octets_from_client{user="hello"} 21862055712 (20.36 GB)
telemt_user_octets_to_client{user="hello"} 400920356956 (373.39 GB)
telemt_user_unique_ips_current{user="hello"} 624
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21682.0 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1404469
telemt_connections_bad_total 234971
telemt_handshake_timeouts_total 13439
telemt_upstream_connect_attempt_total 4026
telemt_upstream_connect_success_total 3894
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 4025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 7333
telemt_me_reconnect_success_total 2800
telemt_me_reader_eof_total 3015
telemt_me_idle_close_by_peer_total 3015
telemt_me_route_drop_no_conn_total 576866
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1044289
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4085
telemt_desync_full_logged_total 1492
telemt_desync_suppressed_total 2593
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 1385
telemt_desync_frames_bucket_total{bucket="gt_10"} 1986
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2989
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2774
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 1043651
telemt_user_connections_current{user="hello"} 2114
telemt_user_octets_from_client{user="hello"} 18546509680 (17.27 GB)
telemt_user_octets_to_client{user="hello"} 516351834608 (480.89 GB)
telemt_user_unique_ips_current{user="hello"} 825
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 26614.9 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390172
telemt_connections_bad_total 11691
telemt_connections_current 569
telemt_connections_me_current 569
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4295
telemt_upstream_connect_attempt_total 8654
telemt_upstream_connect_success_total 8617
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 332918
telemt_me_reconnect_success_total 3446
telemt_me_reader_eof_total 3549
telemt_me_idle_close_by_peer_total 3549
telemt_me_route_drop_no_conn_total 228172
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347431
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 520
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3416
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3435
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 350951
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 7548574469 (7.03 GB)
telemt_user_octets_to_client{user="hello"} 95353648661 (88.81 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 25686.7 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1393975
telemt_connections_bad_total 108039
telemt_connections_current 1902
telemt_connections_me_current 1902
telemt_handshake_timeouts_total 31248
telemt_upstream_connect_attempt_total 4229
telemt_upstream_connect_success_total 4228
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18444
telemt_me_reconnect_success_total 2919
telemt_me_reader_eof_total 3001
telemt_me_idle_close_by_peer_total 3000
telemt_me_route_drop_no_conn_total 615895
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1167133
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5656
telemt_desync_full_logged_total 1834
telemt_desync_suppressed_total 3822
telemt_desync_frames_bucket_total{bucket="1_2"} 1398
telemt_desync_frames_bucket_total{bucket="3_10"} 1898
telemt_desync_frames_bucket_total{bucket="gt_10"} 2360
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2909
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2858
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1165816
telemt_user_connections_current{user="hello"} 1902
telemt_user_octets_from_client{user="hello"} 23104962060 (21.52 GB)
telemt_user_octets_to_client{user="hello"} 683125066144 (636.21 GB)
telemt_user_unique_ips_current{user="hello"} 672
telemt_user_unique_ips_recent_window{user="hello"} 191
```