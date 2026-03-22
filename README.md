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

# Server Metrics 2026-03-22 09:34:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 44900.2 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1133357
telemt_connections_bad_total 61532
telemt_connections_current 1751
telemt_connections_me_current 1751
telemt_handshake_timeouts_total 51940
telemt_upstream_connect_attempt_total 17566
telemt_upstream_connect_success_total 17565
telemt_upstream_connect_attempts_per_request{bucket="1"} 17565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11411
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 496
telemt_me_reconnect_success_total 267
telemt_me_reader_eof_total 267
telemt_me_idle_close_by_peer_total 267
telemt_me_route_drop_no_conn_total 612462
telemt_me_route_drop_channel_closed_total 244
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943112
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 315
telemt_me_single_endpoint_shadow_rotate_total 359
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 6678
telemt_desync_full_logged_total 1920
telemt_desync_suppressed_total 4758
telemt_desync_frames_bucket_total{bucket="1_2"} 1985
telemt_desync_frames_bucket_total{bucket="3_10"} 2511
telemt_desync_frames_bucket_total{bucket="gt_10"} 2182
telemt_pool_swap_total 49
telemt_pool_force_close_total 1394
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 167
telemt_me_draining_writers_reap_progress_total 15959
telemt_me_writer_removed_unexpected_total 263
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1106
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15068
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14565
telemt_me_writer_teardown_success_total{mode="normal"} 16174
telemt_me_writer_teardown_noop_total 15961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32135
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 63.819212
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32135
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 167
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 941409
telemt_user_connections_current{user="hello"} 1751
telemt_user_octets_from_client{user="hello"} 14813036944 (13.80 GB)
telemt_user_octets_to_client{user="hello"} 301648954804 (280.93 GB)
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 58266.6 (16h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1703245
telemt_connections_bad_total 158512
telemt_connections_current 2920
telemt_connections_me_current 2920
telemt_handshake_timeouts_total 45619
telemt_upstream_connect_attempt_total 34735
telemt_upstream_connect_success_total 34287
telemt_upstream_connect_fail_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 34681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 394
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2618
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 1035
telemt_me_idle_close_by_peer_total 1035
telemt_me_route_drop_no_conn_total 915186
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1299693
telemt_me_endpoint_quarantine_total 505
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 461
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
telemt_me_writers_active_current 86
telemt_desync_total 5802
telemt_desync_full_logged_total 3338
telemt_desync_suppressed_total 2464
telemt_desync_frames_bucket_total{bucket="1_2"} 1296
telemt_desync_frames_bucket_total{bucket="3_10"} 2270
telemt_desync_frames_bucket_total{bucket="gt_10"} 2236
telemt_pool_swap_total 59
telemt_pool_force_close_total 1610
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 23633
telemt_me_writer_removed_unexpected_total 1003
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22271
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22023
telemt_me_writer_teardown_success_total{mode="normal"} 24627
telemt_me_writer_teardown_noop_total 23633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48260
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.224912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48260
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 921
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1305843
telemt_user_connections_current{user="hello"} 2920
telemt_user_octets_from_client{user="hello"} 19130925038 (17.82 GB)
telemt_user_octets_to_client{user="hello"} 416556593060 (387.95 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1619
telemt_user_unique_ips_recent_window{user="hello"} 732
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 133126.6 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10367606
telemt_connections_bad_total 922633
telemt_connections_current 5607
telemt_connections_me_current 5607
telemt_handshake_timeouts_total 300224
telemt_upstream_connect_attempt_total 48881
telemt_upstream_connect_success_total 48801
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 48809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1978
telemt_me_reconnect_success_total 1034
telemt_me_reader_eof_total 1031
telemt_me_idle_close_by_peer_total 1030
telemt_me_route_drop_no_conn_total 6360794
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8166373
telemt_me_endpoint_quarantine_total 843
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 993
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
telemt_me_writers_active_current 44
telemt_desync_total 35202
telemt_desync_full_logged_total 11473
telemt_desync_suppressed_total 23729
telemt_desync_frames_bucket_total{bucket="1_2"} 7824
telemt_desync_frames_bucket_total{bucket="3_10"} 13686
telemt_desync_frames_bucket_total{bucket="gt_10"} 13692
telemt_pool_swap_total 143
telemt_pool_force_close_total 4779
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 733
telemt_me_draining_writers_reap_progress_total 44595
telemt_me_writer_removed_unexpected_total 991
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3768
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41275
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4460
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 319
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39816
telemt_me_writer_teardown_success_total{mode="normal"} 45043
telemt_me_writer_teardown_noop_total 44639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89682
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 198.053282
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89682
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 733
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 915
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 8156215
telemt_user_connections_current{user="hello"} 5606
telemt_user_octets_from_client{user="hello"} 131470313980 (122.44 GB)
telemt_user_octets_to_client{user="hello"} 2626851489396 (2.39 TB)
telemt_user_unique_ips_current{user="hello"} 2109
telemt_user_unique_ips_recent_window{user="hello"} 865
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 133128.2 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8344234
telemt_connections_bad_total 750604
telemt_connections_current 4831
telemt_connections_me_current 4831
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 264970
telemt_upstream_connect_attempt_total 55028
telemt_upstream_connect_success_total 54537
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 54784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2985
telemt_me_reconnect_success_total 1160
telemt_me_reader_eof_total 1073
telemt_me_idle_close_by_peer_total 1073
telemt_me_route_drop_no_conn_total 2892861
telemt_me_route_drop_channel_closed_total 342
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6178900
telemt_me_endpoint_quarantine_total 838
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1022
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_me_writers_active_current 90
telemt_desync_total 28329
telemt_desync_full_logged_total 9620
telemt_desync_suppressed_total 18709
telemt_desync_frames_bucket_total{bucket="1_2"} 6851
telemt_desync_frames_bucket_total{bucket="3_10"} 10960
telemt_desync_frames_bucket_total{bucket="gt_10"} 10518
telemt_pool_swap_total 144
telemt_pool_force_close_total 4337
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 473
telemt_me_draining_writers_reap_progress_total 42862
telemt_me_writer_removed_unexpected_total 1091
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3693
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40153
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4075
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 262
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38525
telemt_me_writer_teardown_success_total{mode="normal"} 43846
telemt_me_writer_teardown_noop_total 42868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86714
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.109629
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86714
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 473
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 985
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6101221
telemt_user_connections_current{user="hello"} 4831
telemt_user_octets_from_client{user="hello"} 165080597283 (153.74 GB)
telemt_user_octets_to_client{user="hello"} 2902638371138 (2.64 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1996
telemt_user_unique_ips_recent_window{user="hello"} 683
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 133095.0 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8008406
telemt_connections_bad_total 672211
telemt_connections_current 3906
telemt_connections_me_current 3906
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 263187
telemt_upstream_connect_attempt_total 59636
telemt_upstream_connect_success_total 58945
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27780
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3409
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1340
telemt_me_idle_close_by_peer_total 1340
telemt_me_route_drop_no_conn_total 3285071
telemt_me_route_drop_channel_closed_total 209
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5973223
telemt_me_endpoint_quarantine_total 921
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 977
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 27987
telemt_desync_full_logged_total 9522
telemt_desync_suppressed_total 18465
telemt_desync_frames_bucket_total{bucket="1_2"} 6755
telemt_desync_frames_bucket_total{bucket="3_10"} 10750
telemt_desync_frames_bucket_total{bucket="gt_10"} 10482
telemt_pool_swap_total 140
telemt_pool_force_close_total 4234
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 497
telemt_me_draining_writers_reap_progress_total 43887
telemt_me_writer_removed_unexpected_total 1366
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4103
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41122
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3858
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 376
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39653
telemt_me_writer_teardown_success_total{mode="normal"} 45225
telemt_me_writer_teardown_noop_total 43899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.061096
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89124
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 497
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1277
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 5965860
telemt_user_connections_current{user="hello"} 3906
telemt_user_octets_from_client{user="hello"} 151789526719 (141.37 GB)
telemt_user_octets_to_client{user="hello"} 2631043299759 (2.39 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1529
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 3371.9 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1373933
telemt_connections_bad_total 109575
telemt_connections_current 6575
telemt_connections_me_current 6575
telemt_handshake_timeouts_total 16956
telemt_upstream_connect_attempt_total 7900
telemt_upstream_connect_success_total 7496
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 7832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2663
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 314
telemt_me_reconnect_success_total 112
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 61
telemt_me_route_drop_no_conn_total 2916365
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1131086
telemt_me_endpoint_quarantine_total 18
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 1783
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 1317
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 693
telemt_desync_frames_bucket_total{bucket="gt_10"} 745
telemt_pool_swap_total 2
telemt_pool_force_close_total 95
telemt_me_writer_close_signal_drop_total 45
telemt_me_draining_writers_reap_progress_total 869
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 813
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 44
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 774
telemt_me_writer_teardown_success_total{mode="normal"} 974
telemt_me_writer_teardown_noop_total 869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1843
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.009506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1843
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 45
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 67
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1137156
telemt_user_connections_current{user="hello"} 6575
telemt_user_octets_from_client{user="hello"} 6896418346 (6.42 GB)
telemt_user_octets_to_client{user="hello"} 34939059659 (32.54 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2318
telemt_user_unique_ips_recent_window{user="hello"} 1415
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 133098.6 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7633119
telemt_connections_bad_total 680549
telemt_connections_current 4741
telemt_connections_me_current 4741
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 156964
telemt_upstream_connect_attempt_total 75768
telemt_upstream_connect_success_total 74942
telemt_upstream_connect_fail_total 706
telemt_upstream_connect_attempts_per_request{bucket="1"} 75648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 443
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 706
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70460
telemt_me_reconnect_success_total 2078
telemt_me_reader_eof_total 1823
telemt_me_idle_close_by_peer_total 1822
telemt_me_route_drop_no_conn_total 3083409
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6006140
telemt_me_endpoint_quarantine_total 894
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1003
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 30417
telemt_desync_full_logged_total 10522
telemt_desync_suppressed_total 19895
telemt_desync_frames_bucket_total{bucket="1_2"} 6122
telemt_desync_frames_bucket_total{bucket="3_10"} 11688
telemt_desync_frames_bucket_total{bucket="gt_10"} 12607
telemt_pool_swap_total 138
telemt_pool_force_close_total 3996
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 477
telemt_me_draining_writers_reap_progress_total 46122
telemt_me_writer_removed_unexpected_total 1852
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4700
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43301
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3512
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 484
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42126
telemt_me_writer_teardown_success_total{mode="normal"} 48001
telemt_me_writer_teardown_noop_total 46123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.552958
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94124
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 477
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 1724
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 6004011
telemt_user_connections_current{user="hello"} 4741
telemt_user_octets_from_client{user="hello"} 149661517099 (139.38 GB)
telemt_user_octets_to_client{user="hello"} 2454027929019 (2.23 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1856
telemt_user_unique_ips_recent_window{user="hello"} 688
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 69934.8 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6308589
telemt_connections_bad_total 245393
telemt_connections_current 4433
telemt_connections_me_current 4433
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2546038
telemt_upstream_connect_attempt_total 37140
telemt_upstream_connect_success_total 36880
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 37133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_reconnect_attempts_total 47470
telemt_me_reconnect_success_total 1247
telemt_me_reader_eof_total 912
telemt_me_idle_close_by_peer_total 912
telemt_me_route_drop_no_conn_total 1654338
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3141078
telemt_me_endpoint_quarantine_total 481
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 533
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 17132
telemt_desync_full_logged_total 5786
telemt_desync_suppressed_total 11346
telemt_desync_frames_bucket_total{bucket="1_2"} 3390
telemt_desync_frames_bucket_total{bucket="3_10"} 6561
telemt_desync_frames_bucket_total{bucket="gt_10"} 7181
telemt_pool_swap_total 74
telemt_pool_force_close_total 2246
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 216
telemt_me_draining_writers_reap_progress_total 25146
telemt_me_writer_removed_unexpected_total 983
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2195
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23956
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1931
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 315
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22900
telemt_me_writer_teardown_success_total{mode="normal"} 26151
telemt_me_writer_teardown_noop_total 25152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51303
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.758692
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51303
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 216
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 1114
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3141613
telemt_user_connections_current{user="hello"} 4433
telemt_user_octets_from_client{user="hello"} 78179972092 (72.81 GB)
telemt_user_octets_to_client{user="hello"} 1344707854978 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1721
telemt_user_unique_ips_recent_window{user="hello"} 644
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 50905.2 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481129
telemt_connections_bad_total 3694
telemt_connections_current 1002
telemt_connections_me_current 1002
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9048
telemt_upstream_connect_attempt_total 27038
telemt_upstream_connect_success_total 26975
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 268
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1127
telemt_me_reconnect_success_total 451
telemt_me_reader_eof_total 450
telemt_me_idle_close_by_peer_total 450
telemt_me_route_drop_no_conn_total 156559
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434422
telemt_me_endpoint_quarantine_total 475
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 437
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 2048
telemt_desync_full_logged_total 602
telemt_desync_suppressed_total 1446
telemt_desync_frames_bucket_total{bucket="1_2"} 597
telemt_desync_frames_bucket_total{bucket="3_10"} 795
telemt_desync_frames_bucket_total{bucket="gt_10"} 656
telemt_pool_swap_total 54
telemt_pool_force_close_total 1271
telemt_me_writer_close_signal_drop_total 55
telemt_me_draining_writers_reap_progress_total 21814
telemt_me_writer_removed_unexpected_total 433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1597
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20667
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1220
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20543
telemt_me_writer_teardown_success_total{mode="normal"} 22264
telemt_me_writer_teardown_noop_total 21814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44078
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.103876
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44078
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 55
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 399
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 436508
telemt_user_connections_current{user="hello"} 1002
telemt_user_octets_from_client{user="hello"} 8745120433 (8.14 GB)
telemt_user_octets_to_client{user="hello"} 216705448003 (201.82 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 133103.1 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9384852
telemt_connections_bad_total 1091655
telemt_connections_current 5200
telemt_connections_me_current 5200
telemt_handshake_timeouts_total 256439
telemt_upstream_connect_attempt_total 51423
telemt_upstream_connect_success_total 51226
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 51377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_reconnect_attempts_total 1921
telemt_me_reconnect_success_total 1049
telemt_me_reader_eof_total 1021
telemt_me_idle_close_by_peer_total 1021
telemt_me_route_drop_no_conn_total 2657314
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6962529
telemt_me_endpoint_quarantine_total 940
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1008
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 28153
telemt_desync_full_logged_total 9221
telemt_desync_suppressed_total 18932
telemt_desync_frames_bucket_total{bucket="1_2"} 6950
telemt_desync_frames_bucket_total{bucket="3_10"} 10272
telemt_desync_frames_bucket_total{bucket="gt_10"} 10931
telemt_pool_swap_total 147
telemt_pool_force_close_total 3960
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 46384
telemt_me_writer_removed_unexpected_total 981
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3720
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43676
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 103
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42424
telemt_me_writer_teardown_success_total{mode="normal"} 47396
telemt_me_writer_teardown_noop_total 46386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93782
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.892926
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93782
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 920
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 6935195
telemt_user_connections_current{user="hello"} 5200
telemt_user_octets_from_client{user="hello"} 134927019076 (125.66 GB)
telemt_user_octets_to_client{user="hello"} 3249791892216 (2.96 TB)
telemt_user_unique_ips_current{user="hello"} 1944
telemt_user_unique_ips_recent_window{user="hello"} 739
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 133099.8 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8159354
telemt_connections_bad_total 909342
telemt_connections_current 4594
telemt_connections_me_current 4594
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 214419
telemt_upstream_connect_attempt_total 75890
telemt_upstream_connect_success_total 75353
telemt_upstream_connect_fail_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 75821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30358
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 468
telemt_me_reconnect_attempts_total 6498
telemt_me_reconnect_success_total 1514
telemt_me_reader_eof_total 1345
telemt_me_idle_close_by_peer_total 1345
telemt_me_seq_mismatch_total 63
telemt_me_route_drop_no_conn_total 2858962
telemt_me_route_drop_channel_closed_total 245
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6216653
telemt_me_endpoint_quarantine_total 1038
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1007
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 53
telemt_desync_total 27065
telemt_desync_full_logged_total 8980
telemt_desync_suppressed_total 18085
telemt_desync_frames_bucket_total{bucket="1_2"} 6661
telemt_desync_frames_bucket_total{bucket="3_10"} 9946
telemt_desync_frames_bucket_total{bucket="gt_10"} 10458
telemt_pool_swap_total 144
telemt_pool_force_close_total 3885
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 482
telemt_me_draining_writers_reap_progress_total 45037
telemt_me_writer_removed_unexpected_total 1362
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4365
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42096
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3605
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41152
telemt_me_writer_teardown_success_total{mode="normal"} 46461
telemt_me_writer_teardown_noop_total 45041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91502
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.396744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91502
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 482
telemt_me_refill_failed_total 287
telemt_me_writer_restored_same_endpoint_total 1183
telemt_me_writer_restored_fallback_total 87
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 6225330
telemt_user_connections_current{user="hello"} 4594
telemt_user_octets_from_client{user="hello"} 113868849193 (106.05 GB)
telemt_user_octets_to_client{user="hello"} 2653541310039 (2.41 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1906
telemt_user_unique_ips_recent_window{user="hello"} 663
```