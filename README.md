# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-23 00:55:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 100157.7 (27h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3498181
telemt_connections_bad_total 306324
telemt_connections_current 837
telemt_connections_me_current 837
telemt_handshake_timeouts_total 109203
telemt_upstream_connect_attempt_total 37178
telemt_upstream_connect_success_total 37177
telemt_upstream_connect_attempts_per_request{bucket="1"} 37177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1389
telemt_me_reconnect_success_total 596
telemt_me_reader_eof_total 612
telemt_me_idle_close_by_peer_total 612
telemt_me_route_drop_no_conn_total 2981480
telemt_me_route_drop_channel_closed_total 1231
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2890856
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 705
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 781
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 12405
telemt_desync_full_logged_total 3888
telemt_desync_suppressed_total 8517
telemt_desync_frames_bucket_total{bucket="1_2"} 3349
telemt_desync_frames_bucket_total{bucket="3_10"} 4510
telemt_desync_frames_bucket_total{bucket="gt_10"} 4546
telemt_pool_swap_total 111
telemt_pool_force_close_total 3430
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 34049
telemt_me_writer_removed_unexpected_total 590
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31824
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3374
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30619
telemt_me_writer_teardown_success_total{mode="normal"} 34287
telemt_me_writer_teardown_noop_total 34060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68347
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 376.256395
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68347
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 533
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2879963
telemt_user_connections_current{user="hello"} 837
telemt_user_octets_from_client{user="hello"} 41036562156 (38.22 GB)
telemt_user_octets_to_client{user="hello"} 788039639856 (733.92 GB)
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 113523.7 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3995245
telemt_connections_bad_total 366754
telemt_connections_current 421
telemt_connections_me_current 421
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100634
telemt_upstream_connect_attempt_total 70500
telemt_upstream_connect_success_total 69657
telemt_upstream_connect_fail_total 750
telemt_upstream_connect_attempts_per_request{bucket="1"} 70407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 750
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9964
telemt_me_reconnect_success_total 3596
telemt_me_reader_eof_total 3594
telemt_me_idle_close_by_peer_total 3594
telemt_me_route_drop_no_conn_total 3640547
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3175723
telemt_me_endpoint_quarantine_total 899
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 883
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 40
telemt_desync_total 12950
telemt_desync_full_logged_total 7260
telemt_desync_suppressed_total 5690
telemt_desync_frames_bucket_total{bucket="1_2"} 2939
telemt_desync_frames_bucket_total{bucket="3_10"} 5076
telemt_desync_frames_bucket_total{bucket="gt_10"} 4935
telemt_pool_swap_total 106
telemt_pool_force_close_total 3052
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 46581
telemt_me_writer_removed_unexpected_total 3526
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6149
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43989
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43529
telemt_me_writer_teardown_success_total{mode="normal"} 50138
telemt_me_writer_teardown_noop_total 46582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96720
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.592765
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96720
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 245
telemt_me_writer_restored_same_endpoint_total 3219
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 3188561
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 43055783691 (40.10 GB)
telemt_user_octets_to_client{user="hello"} 790971807243 (736.65 GB)
telemt_user_msgs_from_client{user="hello"} 48526
telemt_user_msgs_to_client{user="hello"} 183196
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 188383.5 (52h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16321980
telemt_connections_bad_total 1644192
telemt_connections_current 742
telemt_connections_me_current 742
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397288
telemt_upstream_connect_attempt_total 84338
telemt_upstream_connect_success_total 84233
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 84250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1717
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2994
telemt_me_reconnect_success_total 1571
telemt_me_reader_eof_total 1518
telemt_me_idle_close_by_peer_total 1516
telemt_me_route_drop_no_conn_total 14044214
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12966248
telemt_me_endpoint_quarantine_total 1244
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1417
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 53765
telemt_desync_full_logged_total 17068
telemt_desync_suppressed_total 36697
telemt_desync_frames_bucket_total{bucket="1_2"} 11981
telemt_desync_frames_bucket_total{bucket="3_10"} 20974
telemt_desync_frames_bucket_total{bucket="gt_10"} 20810
telemt_pool_swap_total 204
telemt_pool_force_close_total 6701
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1060
telemt_me_draining_writers_reap_progress_total 63790
telemt_me_writer_removed_unexpected_total 1462
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59064
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6231
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57089
telemt_me_writer_teardown_success_total{mode="normal"} 64527
telemt_me_writer_teardown_noop_total 63843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128370
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.692470
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128370
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1060
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1359
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12966283
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 191081493869 (177.96 GB)
telemt_user_octets_to_client{user="hello"} 3487584547927 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 188385.0 (52h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11870087
telemt_connections_bad_total 1233463
telemt_connections_current 590
telemt_connections_me_current 590
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344551
telemt_upstream_connect_attempt_total 98716
telemt_upstream_connect_success_total 97392
telemt_upstream_connect_fail_total 871
telemt_upstream_connect_attempts_per_request{bucket="1"} 98263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 871
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4427
telemt_me_reconnect_success_total 1876
telemt_me_reader_eof_total 1744
telemt_me_idle_close_by_peer_total 1744
telemt_me_route_drop_no_conn_total 4554461
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8811836
telemt_me_endpoint_quarantine_total 1255
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1436
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 38760
telemt_desync_full_logged_total 13053
telemt_desync_suppressed_total 25707
telemt_desync_frames_bucket_total{bucket="1_2"} 9603
telemt_desync_frames_bucket_total{bucket="3_10"} 14887
telemt_desync_frames_bucket_total{bucket="gt_10"} 14270
telemt_pool_swap_total 201
telemt_pool_force_close_total 6059
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 709
telemt_me_draining_writers_reap_progress_total 62016
telemt_me_writer_removed_unexpected_total 1774
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5554
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58092
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55957
telemt_me_writer_teardown_success_total{mode="normal"} 63646
telemt_me_writer_teardown_noop_total 62041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125687
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.417853
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125687
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 709
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8749598
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 217748386248 (202.79 GB)
telemt_user_octets_to_client{user="hello"} 3960952181619 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 188349.0 (52h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11048609
telemt_connections_bad_total 973301
telemt_connections_current 392
telemt_connections_me_current 392
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345551
telemt_upstream_connect_attempt_total 82995
telemt_upstream_connect_success_total 81436
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 81641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5739
telemt_me_reconnect_success_total 2363
telemt_me_reader_eof_total 2108
telemt_me_idle_close_by_peer_total 2107
telemt_me_route_drop_no_conn_total 5336238
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8352018
telemt_me_endpoint_quarantine_total 1324
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1393
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 38105
telemt_desync_full_logged_total 12626
telemt_desync_suppressed_total 25479
telemt_desync_frames_bucket_total{bucket="1_2"} 9619
telemt_desync_frames_bucket_total{bucket="3_10"} 14581
telemt_desync_frames_bucket_total{bucket="gt_10"} 13905
telemt_pool_swap_total 197
telemt_pool_force_close_total 5961
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 739
telemt_me_draining_writers_reap_progress_total 62418
telemt_me_writer_removed_unexpected_total 2258
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6303
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58305
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5390
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56457
telemt_me_writer_teardown_success_total{mode="normal"} 64608
telemt_me_writer_teardown_noop_total 62489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127097
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.780909
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127097
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 739
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2053
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8343981
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 192708011699 (179.47 GB)
telemt_user_octets_to_client{user="hello"} 3469284073693 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 58629.3 (16h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11229203
telemt_connections_bad_total 668658
telemt_connections_current 870
telemt_connections_me_current 870
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 270621
telemt_upstream_connect_attempt_total 56803
telemt_upstream_connect_success_total 53908
telemt_upstream_connect_fail_total 1911
telemt_upstream_connect_attempts_per_request{bucket="1"} 55819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6006
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1911
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7510
telemt_me_reconnect_success_total 1186
telemt_me_reader_eof_total 757
telemt_me_idle_close_by_peer_total 756
telemt_me_route_drop_no_conn_total 25288728
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9320919
telemt_me_endpoint_quarantine_total 439
telemt_me_single_endpoint_outage_enter_total 86
telemt_me_single_endpoint_outage_exit_total 86
telemt_me_single_endpoint_outage_reconnect_attempt_total 159
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 159
telemt_me_single_endpoint_shadow_rotate_total 462
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 16304
telemt_desync_full_logged_total 4441
telemt_desync_suppressed_total 11863
telemt_desync_frames_bucket_total{bucket="1_2"} 3090
telemt_desync_frames_bucket_total{bucket="3_10"} 6635
telemt_desync_frames_bucket_total{bucket="gt_10"} 6579
telemt_pool_swap_total 61
telemt_pool_force_close_total 1986
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 478
telemt_me_draining_writers_reap_progress_total 18297
telemt_me_writer_removed_unexpected_total 1072
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2446
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16865
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16311
telemt_me_writer_teardown_success_total{mode="normal"} 19311
telemt_me_writer_teardown_noop_total 18316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37627
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.681781
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37627
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 478
telemt_me_refill_failed_total 337
telemt_me_writer_restored_same_endpoint_total 774
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 9346249
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 87204742510 (81.22 GB)
telemt_user_octets_to_client{user="hello"} 604918773137 (563.37 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 188355.7 (52h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10986100
telemt_connections_bad_total 946533
telemt_connections_current 525
telemt_connections_me_current 525
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241989
telemt_upstream_connect_attempt_total 111928
telemt_upstream_connect_success_total 110772
telemt_upstream_connect_fail_total 983
telemt_upstream_connect_attempts_per_request{bucket="1"} 111755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 983
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72878
telemt_me_reconnect_success_total 3073
telemt_me_reader_eof_total 2760
telemt_me_idle_close_by_peer_total 2758
telemt_me_route_drop_no_conn_total 5261267
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8670389
telemt_me_endpoint_quarantine_total 1271
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1423
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 46214
telemt_desync_full_logged_total 15822
telemt_desync_suppressed_total 30392
telemt_desync_frames_bucket_total{bucket="1_2"} 9391
telemt_desync_frames_bucket_total{bucket="3_10"} 17688
telemt_desync_frames_bucket_total{bucket="gt_10"} 19135
telemt_pool_swap_total 193
telemt_pool_force_close_total 5665
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 663
telemt_me_draining_writers_reap_progress_total 66605
telemt_me_writer_removed_unexpected_total 2789
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6826
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62603
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60940
telemt_me_writer_teardown_success_total{mode="normal"} 69429
telemt_me_writer_teardown_noop_total 66606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136035
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.263878
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136035
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 663
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2592
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8673392
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 194551381189 (181.19 GB)
telemt_user_octets_to_client{user="hello"} 3313823976880 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 125191.9 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11688709
telemt_connections_bad_total 482173
telemt_connections_current 711
telemt_connections_me_current 711
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4760124
telemt_upstream_connect_attempt_total 60157
telemt_upstream_connect_success_total 59717
telemt_upstream_connect_fail_total 429
telemt_upstream_connect_attempts_per_request{bucket="1"} 60146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 429
telemt_me_reconnect_attempts_total 48899
telemt_me_reconnect_success_total 1808
telemt_me_reader_eof_total 1479
telemt_me_idle_close_by_peer_total 1478
telemt_me_route_drop_no_conn_total 4086637
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5615440
telemt_me_endpoint_quarantine_total 841
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 957
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 29
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31549
telemt_desync_full_logged_total 10757
telemt_desync_suppressed_total 20792
telemt_desync_frames_bucket_total{bucket="1_2"} 6277
telemt_desync_frames_bucket_total{bucket="3_10"} 12445
telemt_desync_frames_bucket_total{bucket="gt_10"} 12827
telemt_pool_swap_total 132
telemt_pool_force_close_total 3876
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 45725
telemt_me_writer_removed_unexpected_total 1530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3764
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43534
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41849
telemt_me_writer_teardown_success_total{mode="normal"} 47298
telemt_me_writer_teardown_noop_total 45732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.686040
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2736
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5607975
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 119064543336 (110.89 GB)
telemt_user_octets_to_client{user="hello"} 2170246149238 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 106162.6 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1517535
telemt_connections_bad_total 36717
telemt_connections_current 384
telemt_connections_me_current 384
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30529
telemt_upstream_connect_attempt_total 49951
telemt_upstream_connect_success_total 49795
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 49923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 788
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2243
telemt_me_reconnect_success_total 908
telemt_me_reader_eof_total 895
telemt_me_idle_close_by_peer_total 895
telemt_me_route_drop_no_conn_total 516821
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1348628
telemt_me_endpoint_quarantine_total 871
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 876
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 8910
telemt_desync_full_logged_total 2612
telemt_desync_suppressed_total 6298
telemt_desync_frames_bucket_total{bucket="1_2"} 2476
telemt_desync_frames_bucket_total{bucket="3_10"} 3408
telemt_desync_frames_bucket_total{bucket="gt_10"} 3026
telemt_pool_swap_total 114
telemt_pool_force_close_total 2926
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 42196
telemt_me_writer_removed_unexpected_total 863
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3237
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39861
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2838
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39270
telemt_me_writer_teardown_success_total{mode="normal"} 43098
telemt_me_writer_teardown_noop_total 42200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85298
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.244113
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85298
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 773
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1344440
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 25948230097 (24.17 GB)
telemt_user_octets_to_client{user="hello"} 574267529599 (534.83 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 188360.1 (52h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13319186
telemt_connections_bad_total 1600725
telemt_connections_current 535
telemt_connections_me_current 535
telemt_handshake_timeouts_total 388565
telemt_upstream_connect_attempt_total 73942
telemt_upstream_connect_success_total 73592
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 73806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2966
telemt_me_reconnect_success_total 1483
telemt_me_reader_eof_total 1467
telemt_me_idle_close_by_peer_total 1467
telemt_me_route_drop_no_conn_total 4482186
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10043691
telemt_me_endpoint_quarantine_total 1345
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1424
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 42050
telemt_desync_full_logged_total 13735
telemt_desync_suppressed_total 28315
telemt_desync_frames_bucket_total{bucket="1_2"} 10168
telemt_desync_frames_bucket_total{bucket="3_10"} 15453
telemt_desync_frames_bucket_total{bucket="gt_10"} 16429
telemt_pool_swap_total 209
telemt_pool_force_close_total 5583
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 66814
telemt_me_writer_removed_unexpected_total 1405
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5287
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62984
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5409
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61231
telemt_me_writer_teardown_success_total{mode="normal"} 68271
telemt_me_writer_teardown_noop_total 66816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135087
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.771296
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135087
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1300
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 10010404
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 194742107244 (181.37 GB)
telemt_user_octets_to_client{user="hello"} 4437960432996 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 188356.9 (52h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11631520
telemt_connections_bad_total 1356122
telemt_connections_current 469
telemt_connections_me_current 469
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311260
telemt_upstream_connect_attempt_total 101424
telemt_upstream_connect_success_total 100536
telemt_upstream_connect_fail_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 101216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 680
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10464
telemt_me_reconnect_success_total 2573
telemt_me_reader_eof_total 2385
telemt_me_idle_close_by_peer_total 2384
telemt_me_seq_mismatch_total 97
telemt_me_route_drop_no_conn_total 5649322
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8953600
telemt_me_endpoint_quarantine_total 1521
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1426
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 41761
telemt_desync_full_logged_total 13446
telemt_desync_suppressed_total 28315
telemt_desync_frames_bucket_total{bucket="1_2"} 10774
telemt_desync_frames_bucket_total{bucket="3_10"} 15362
telemt_desync_frames_bucket_total{bucket="gt_10"} 15625
telemt_pool_swap_total 199
telemt_pool_force_close_total 5361
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 66856
telemt_me_writer_removed_unexpected_total 2427
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6634
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62733
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4890
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61495
telemt_me_writer_teardown_success_total{mode="normal"} 69367
telemt_me_writer_teardown_noop_total 66861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136228
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.461471
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136228
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2069
telemt_me_writer_restored_fallback_total 132
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 8958199
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 157332229500 (146.53 GB)
telemt_user_octets_to_client{user="hello"} 3487950782430 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 50
```