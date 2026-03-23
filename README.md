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

# Server Metrics 2026-03-23 00:20:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 98021.6 (27h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3452883
telemt_connections_bad_total 295388
telemt_connections_current 807
telemt_connections_me_current 807
telemt_handshake_timeouts_total 108101
telemt_upstream_connect_attempt_total 36267
telemt_upstream_connect_success_total 36266
telemt_upstream_connect_attempts_per_request{bucket="1"} 36266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23544
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1377
telemt_me_reconnect_success_total 584
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 2976367
telemt_me_route_drop_channel_closed_total 1231
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2861568
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 675
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 761
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
telemt_me_writers_active_current 45
telemt_desync_total 12332
telemt_desync_full_logged_total 3857
telemt_desync_suppressed_total 8475
telemt_desync_frames_bucket_total{bucket="1_2"} 3329
telemt_desync_frames_bucket_total{bucket="3_10"} 4486
telemt_desync_frames_bucket_total{bucket="gt_10"} 4517
telemt_pool_swap_total 108
telemt_pool_force_close_total 3352
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 647
telemt_me_draining_writers_reap_progress_total 33209
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2407
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31028
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3296
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29857
telemt_me_writer_teardown_success_total{mode="normal"} 33435
telemt_me_writer_teardown_noop_total 33220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66655
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 376.085392
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66655
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 647
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2850787
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 40816899756 (38.01 GB)
telemt_user_octets_to_client{user="hello"} 779980009808 (726.41 GB)
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 111387.9 (30h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3983618
telemt_connections_bad_total 363783
telemt_connections_current 413
telemt_connections_me_current 413
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100385
telemt_upstream_connect_attempt_total 68834
telemt_upstream_connect_success_total 68008
telemt_upstream_connect_fail_total 733
telemt_upstream_connect_attempts_per_request{bucket="1"} 68741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 733
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9812
telemt_me_reconnect_success_total 3555
telemt_me_reader_eof_total 3561
telemt_me_idle_close_by_peer_total 3561
telemt_me_route_drop_no_conn_total 3639431
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3167940
telemt_me_endpoint_quarantine_total 858
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 866
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 45
telemt_desync_total 12920
telemt_desync_full_logged_total 7241
telemt_desync_suppressed_total 5679
telemt_desync_frames_bucket_total{bucket="1_2"} 2934
telemt_desync_frames_bucket_total{bucket="3_10"} 5064
telemt_desync_frames_bucket_total{bucket="gt_10"} 4922
telemt_pool_swap_total 103
telemt_pool_force_close_total 3031
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 246
telemt_me_draining_writers_reap_progress_total 45404
telemt_me_writer_removed_unexpected_total 3493
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6053
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42875
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42373
telemt_me_writer_teardown_success_total{mode="normal"} 48928
telemt_me_writer_teardown_noop_total 45405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94333
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.568059
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94333
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 246
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 3193
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 3180421
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 42929086130 (39.98 GB)
telemt_user_octets_to_client{user="hello"} 788897558480 (734.72 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 186247.7 (51h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16301449
telemt_connections_bad_total 1641963
telemt_connections_current 896
telemt_connections_me_current 896
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396889
telemt_upstream_connect_attempt_total 83161
telemt_upstream_connect_success_total 83058
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 83075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1711
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2973
telemt_me_reconnect_success_total 1551
telemt_me_reader_eof_total 1498
telemt_me_idle_close_by_peer_total 1496
telemt_me_route_drop_no_conn_total 14041307
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12948913
telemt_me_endpoint_quarantine_total 1223
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1396
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_active_current 44
telemt_desync_total 53650
telemt_desync_full_logged_total 17018
telemt_desync_suppressed_total 36632
telemt_desync_frames_bucket_total{bucket="1_2"} 11946
telemt_desync_frames_bucket_total{bucket="3_10"} 20922
telemt_desync_frames_bucket_total{bucket="gt_10"} 20782
telemt_pool_swap_total 201
telemt_pool_force_close_total 6644
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1056
telemt_me_draining_writers_reap_progress_total 62720
telemt_me_writer_removed_unexpected_total 1443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5385
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58052
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6174
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56076
telemt_me_writer_teardown_success_total{mode="normal"} 63437
telemt_me_writer_teardown_noop_total 62773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126210
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.551947
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126210
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1056
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1342
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 12948973
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 190921300617 (177.81 GB)
telemt_user_octets_to_client{user="hello"} 3482964910603 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 186249.1 (51h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11841725
telemt_connections_bad_total 1225863
telemt_connections_current 575
telemt_connections_me_current 575
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344423
telemt_upstream_connect_attempt_total 97506
telemt_upstream_connect_success_total 96187
telemt_upstream_connect_fail_total 866
telemt_upstream_connect_attempts_per_request{bucket="1"} 97053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3800
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 866
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4385
telemt_me_reconnect_success_total 1853
telemt_me_reader_eof_total 1718
telemt_me_idle_close_by_peer_total 1718
telemt_me_route_drop_no_conn_total 4551864
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8795496
telemt_me_endpoint_quarantine_total 1225
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1418
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 38694
telemt_desync_full_logged_total 13023
telemt_desync_suppressed_total 25671
telemt_desync_frames_bucket_total{bucket="1_2"} 9586
telemt_desync_frames_bucket_total{bucket="3_10"} 14860
telemt_desync_frames_bucket_total{bucket="gt_10"} 14248
telemt_pool_swap_total 198
telemt_pool_force_close_total 6001
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 60937
telemt_me_writer_removed_unexpected_total 1749
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5485
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57056
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54936
telemt_me_writer_teardown_success_total{mode="normal"} 62541
telemt_me_writer_teardown_noop_total 60962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123503
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.384369
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123503
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 1583
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 8733268
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 217667484532 (202.72 GB)
telemt_user_octets_to_client{user="hello"} 3954181455847 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 186213.1 (51h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11030153
telemt_connections_bad_total 970214
telemt_connections_current 438
telemt_connections_me_current 438
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345417
telemt_upstream_connect_attempt_total 81795
telemt_upstream_connect_success_total 80237
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 80442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5700
telemt_me_reconnect_success_total 2342
telemt_me_reader_eof_total 2084
telemt_me_idle_close_by_peer_total 2083
telemt_me_route_drop_no_conn_total 5333756
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8339842
telemt_me_endpoint_quarantine_total 1302
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1376
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_active_current 44
telemt_desync_total 38003
telemt_desync_full_logged_total 12599
telemt_desync_suppressed_total 25404
telemt_desync_frames_bucket_total{bucket="1_2"} 9600
telemt_desync_frames_bucket_total{bucket="3_10"} 14533
telemt_desync_frames_bucket_total{bucket="gt_10"} 13870
telemt_pool_swap_total 194
telemt_pool_force_close_total 5902
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 737
telemt_me_draining_writers_reap_progress_total 61305
telemt_me_writer_removed_unexpected_total 2236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6237
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57234
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5331
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55403
telemt_me_writer_teardown_success_total{mode="normal"} 63471
telemt_me_writer_teardown_noop_total 61376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124847
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.679462
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124847
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 737
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2033
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8331813
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 192559399815 (179.33 GB)
telemt_user_octets_to_client{user="hello"} 3463681250177 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 56493.6 (15h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11195944
telemt_connections_bad_total 668518
telemt_connections_current 945
telemt_connections_me_current 945
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 266114
telemt_upstream_connect_attempt_total 55771
telemt_upstream_connect_success_total 52913
telemt_upstream_connect_fail_total 1903
telemt_upstream_connect_attempts_per_request{bucket="1"} 54816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6005
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1903
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7471
telemt_me_reconnect_success_total 1168
telemt_me_reader_eof_total 742
telemt_me_idle_close_by_peer_total 741
telemt_me_route_drop_no_conn_total 25280134
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9297040
telemt_me_endpoint_quarantine_total 412
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 445
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_active_current 46
telemt_desync_total 16262
telemt_desync_full_logged_total 4414
telemt_desync_suppressed_total 11848
telemt_desync_frames_bucket_total{bucket="1_2"} 3086
telemt_desync_frames_bucket_total{bucket="3_10"} 6609
telemt_desync_frames_bucket_total{bucket="gt_10"} 6567
telemt_pool_swap_total 58
telemt_pool_force_close_total 1936
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 474
telemt_me_draining_writers_reap_progress_total 17368
telemt_me_writer_removed_unexpected_total 1057
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2375
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1629
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15432
telemt_me_writer_teardown_success_total{mode="normal"} 18367
telemt_me_writer_teardown_noop_total 17387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35754
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.564265
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35754
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 474
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 9322492
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 86829893730 (80.87 GB)
telemt_user_octets_to_client{user="hello"} 599212608937 (558.06 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 186220.0 (51h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10964616
telemt_connections_bad_total 942444
telemt_connections_current 747
telemt_connections_me_current 747
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241789
telemt_upstream_connect_attempt_total 110702
telemt_upstream_connect_success_total 109564
telemt_upstream_connect_fail_total 965
telemt_upstream_connect_attempts_per_request{bucket="1"} 110529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42416
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 965
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72830
telemt_me_reconnect_success_total 3037
telemt_me_reader_eof_total 2730
telemt_me_idle_close_by_peer_total 2728
telemt_me_route_drop_no_conn_total 5257126
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8654131
telemt_me_endpoint_quarantine_total 1240
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1404
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 45
telemt_desync_total 46147
telemt_desync_full_logged_total 15796
telemt_desync_suppressed_total 30351
telemt_desync_frames_bucket_total{bucket="1_2"} 9374
telemt_desync_frames_bucket_total{bucket="3_10"} 17665
telemt_desync_frames_bucket_total{bucket="gt_10"} 19108
telemt_pool_swap_total 190
telemt_pool_force_close_total 5606
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 65480
telemt_me_writer_removed_unexpected_total 2760
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6744
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61530
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59874
telemt_me_writer_teardown_success_total{mode="normal"} 68274
telemt_me_writer_teardown_noop_total 65481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133755
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.220463
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133755
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2568
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8657167
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 194405108497 (181.05 GB)
telemt_user_octets_to_client{user="hello"} 3305737841044 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 123056.1 (34h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11661028
telemt_connections_bad_total 476590
telemt_connections_current 488
telemt_connections_me_current 488
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4759481
telemt_upstream_connect_attempt_total 58903
telemt_upstream_connect_success_total 58474
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 58891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_reconnect_attempts_total 48851
telemt_me_reconnect_success_total 1781
telemt_me_reader_eof_total 1452
telemt_me_idle_close_by_peer_total 1451
telemt_me_route_drop_no_conn_total 4083409
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5602443
telemt_me_endpoint_quarantine_total 828
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 941
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 48
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31488
telemt_desync_full_logged_total 10729
telemt_desync_suppressed_total 20759
telemt_desync_frames_bucket_total{bucket="1_2"} 6269
telemt_desync_frames_bucket_total{bucket="3_10"} 12417
telemt_desync_frames_bucket_total{bucket="gt_10"} 12802
telemt_pool_swap_total 130
telemt_pool_force_close_total 3842
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 44627
telemt_me_writer_removed_unexpected_total 1503
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3707
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42466
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3401
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40785
telemt_me_writer_teardown_success_total{mode="normal"} 46173
telemt_me_writer_teardown_noop_total 44634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90807
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.678500
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90807
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2735
telemt_me_writer_restored_same_endpoint_total 1582
telemt_me_writer_restored_fallback_total 23
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5595016
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 118952736772 (110.78 GB)
telemt_user_octets_to_client{user="hello"} 2164845120998 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 104026.7 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1505366
telemt_connections_bad_total 36680
telemt_connections_current 413
telemt_connections_me_current 413
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30167
telemt_upstream_connect_attempt_total 48742
telemt_upstream_connect_success_total 48587
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 48714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 784
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2207
telemt_me_reconnect_success_total 891
telemt_me_reader_eof_total 875
telemt_me_idle_close_by_peer_total 875
telemt_me_route_drop_no_conn_total 515026
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1337471
telemt_me_endpoint_quarantine_total 846
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 860
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 8728
telemt_desync_full_logged_total 2578
telemt_desync_suppressed_total 6150
telemt_desync_frames_bucket_total{bucket="1_2"} 2373
telemt_desync_frames_bucket_total{bucket="3_10"} 3346
telemt_desync_frames_bucket_total{bucket="gt_10"} 3009
telemt_pool_swap_total 112
telemt_pool_force_close_total 2892
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 161
telemt_me_draining_writers_reap_progress_total 41097
telemt_me_writer_removed_unexpected_total 845
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3185
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38794
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2804
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38205
telemt_me_writer_teardown_success_total{mode="normal"} 41979
telemt_me_writer_teardown_noop_total 41101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83080
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.195207
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83080
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 161
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 756
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1333295
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 25828188093 (24.05 GB)
telemt_user_octets_to_client{user="hello"} 571699124647 (532.44 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 186224.3 (51h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13300883
telemt_connections_bad_total 1597717
telemt_connections_current 625
telemt_connections_me_current 625
telemt_handshake_timeouts_total 387690
telemt_upstream_connect_attempt_total 72621
telemt_upstream_connect_success_total 72275
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 72485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2918
telemt_me_reconnect_success_total 1452
telemt_me_reader_eof_total 1438
telemt_me_idle_close_by_peer_total 1438
telemt_me_route_drop_no_conn_total 4480055
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10029830
telemt_me_endpoint_quarantine_total 1300
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1404
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 46
telemt_desync_total 41960
telemt_desync_full_logged_total 13701
telemt_desync_suppressed_total 28259
telemt_desync_frames_bucket_total{bucket="1_2"} 10127
telemt_desync_frames_bucket_total{bucket="3_10"} 15426
telemt_desync_frames_bucket_total{bucket="gt_10"} 16407
telemt_pool_swap_total 206
telemt_pool_force_close_total 5536
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 674
telemt_me_draining_writers_reap_progress_total 65599
telemt_me_writer_removed_unexpected_total 1376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5195
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61832
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60063
telemt_me_writer_teardown_success_total{mode="normal"} 67027
telemt_me_writer_teardown_noop_total 65601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132628
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.744940
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132628
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 674
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1274
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 9996557
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 194473945040 (181.12 GB)
telemt_user_octets_to_client{user="hello"} 4433546207216 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 186221.0 (51h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11604240
telemt_connections_bad_total 1346314
telemt_connections_current 524
telemt_connections_me_current 524
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 310301
telemt_upstream_connect_attempt_total 99341
telemt_upstream_connect_success_total 98462
telemt_upstream_connect_fail_total 671
telemt_upstream_connect_attempts_per_request{bucket="1"} 99133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42030
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 671
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10335
telemt_me_reconnect_success_total 2547
telemt_me_reader_eof_total 2363
telemt_me_idle_close_by_peer_total 2362
telemt_me_seq_mismatch_total 95
telemt_me_route_drop_no_conn_total 5642391
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8937944
telemt_me_endpoint_quarantine_total 1483
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1407
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_active_current 47
telemt_desync_total 41699
telemt_desync_full_logged_total 13408
telemt_desync_suppressed_total 28291
telemt_desync_frames_bucket_total{bucket="1_2"} 10748
telemt_desync_frames_bucket_total{bucket="3_10"} 15331
telemt_desync_frames_bucket_total{bucket="gt_10"} 15620
telemt_pool_swap_total 196
telemt_pool_force_close_total 5329
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 661
telemt_me_draining_writers_reap_progress_total 65611
telemt_me_writer_removed_unexpected_total 2404
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6561
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61537
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4858
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60282
telemt_me_writer_teardown_success_total{mode="normal"} 68098
telemt_me_writer_teardown_noop_total 65616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133714
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.444111
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133714
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 661
telemt_me_refill_failed_total 403
telemt_me_writer_restored_same_endpoint_total 2056
telemt_me_writer_restored_fallback_total 130
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 8942887
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 157178802301 (146.38 GB)
telemt_user_octets_to_client{user="hello"} 3480092792319 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 64
```