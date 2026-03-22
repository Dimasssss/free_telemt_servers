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

# Server Metrics 2026-03-22 17:35:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 73761.5 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2662794
telemt_connections_bad_total 144807
telemt_connections_current 1443
telemt_connections_me_current 1443
telemt_handshake_timeouts_total 91701
telemt_upstream_connect_attempt_total 27129
telemt_upstream_connect_success_total 27128
telemt_upstream_connect_attempts_per_request{bucket="1"} 27128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17630
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1094
telemt_me_reconnect_success_total 467
telemt_me_reader_eof_total 469
telemt_me_idle_close_by_peer_total 469
telemt_me_route_drop_no_conn_total 2206625
telemt_me_route_drop_channel_closed_total 907
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2272583
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 503
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 575
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 10555
telemt_desync_full_logged_total 3339
telemt_desync_suppressed_total 7216
telemt_desync_frames_bucket_total{bucket="1_2"} 2827
telemt_desync_frames_bucket_total{bucket="3_10"} 3929
telemt_desync_frames_bucket_total{bucket="gt_10"} 3799
telemt_pool_swap_total 81
telemt_pool_force_close_total 2515
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 24782
telemt_me_writer_removed_unexpected_total 455
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1813
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23195
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2463
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22267
telemt_me_writer_teardown_success_total{mode="normal"} 25008
telemt_me_writer_teardown_noop_total 24792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49800
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 243.816895
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49800
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 413
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2268841
telemt_user_connections_current{user="hello"} 1443
telemt_user_octets_from_client{user="hello"} 33433842784 (31.14 GB)
telemt_user_octets_to_client{user="hello"} 599262881060 (558.11 GB)
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 87128.2 (24h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3680297
telemt_connections_bad_total 333303
telemt_connections_current 1042
telemt_connections_me_current 1042
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 92775
telemt_upstream_connect_attempt_total 53897
telemt_upstream_connect_success_total 53226
telemt_upstream_connect_fail_total 591
telemt_upstream_connect_attempts_per_request{bucket="1"} 53817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 591
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6235
telemt_me_reconnect_success_total 2262
telemt_me_reader_eof_total 2192
telemt_me_idle_close_by_peer_total 2192
telemt_me_route_drop_no_conn_total 3554871
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2919774
telemt_me_endpoint_quarantine_total 689
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 672
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
telemt_desync_total 11489
telemt_desync_full_logged_total 6418
telemt_desync_suppressed_total 5071
telemt_desync_frames_bucket_total{bucket="1_2"} 2675
telemt_desync_frames_bucket_total{bucket="3_10"} 4512
telemt_desync_frames_bucket_total{bucket="gt_10"} 4302
telemt_pool_swap_total 82
telemt_pool_force_close_total 2461
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 34591
telemt_me_writer_removed_unexpected_total 2144
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4131
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32613
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2101
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32130
telemt_me_writer_teardown_success_total{mode="normal"} 36744
telemt_me_writer_teardown_noop_total 34591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71335
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.233696
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71335
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 157
telemt_me_writer_restored_same_endpoint_total 1953
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 2930977
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 37322845039 (34.76 GB)
telemt_user_octets_to_client{user="hello"} 666412529606 (620.65 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 600
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 161988.8 (44h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15560531
telemt_connections_bad_total 1488256
telemt_connections_current 2696
telemt_connections_me_current 2696
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 381202
telemt_upstream_connect_attempt_total 72754
telemt_upstream_connect_success_total 72657
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 72674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2703
telemt_me_reconnect_success_total 1391
telemt_me_reader_eof_total 1329
telemt_me_idle_close_by_peer_total 1327
telemt_me_route_drop_no_conn_total 13863396
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12403413
telemt_me_endpoint_quarantine_total 1016
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1205
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 50762
telemt_desync_full_logged_total 15942
telemt_desync_suppressed_total 34820
telemt_desync_frames_bucket_total{bucket="1_2"} 11339
telemt_desync_frames_bucket_total{bucket="3_10"} 19814
telemt_desync_frames_bucket_total{bucket="gt_10"} 19609
telemt_pool_swap_total 174
telemt_pool_force_close_total 5908
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 955
telemt_me_draining_writers_reap_progress_total 53219
telemt_me_writer_removed_unexpected_total 1283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49140
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47311
telemt_me_writer_teardown_success_total{mode="normal"} 53793
telemt_me_writer_teardown_noop_total 53269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107062
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 303.645722
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107062
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 955
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1196
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12404388
telemt_user_connections_current{user="hello"} 2696
telemt_user_octets_from_client{user="hello"} 179048568809 (166.75 GB)
telemt_user_octets_to_client{user="hello"} 3230272672843 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1053
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 161988.7 (44h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11216777
telemt_connections_bad_total 1093706
telemt_connections_current 1583
telemt_connections_me_current 1583
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 336481
telemt_upstream_connect_attempt_total 85118
telemt_upstream_connect_success_total 83945
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 84783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3699
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 4036
telemt_me_reconnect_success_total 1666
telemt_me_reader_eof_total 1535
telemt_me_idle_close_by_peer_total 1535
telemt_me_route_drop_no_conn_total 4404631
telemt_me_route_drop_channel_closed_total 488
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8360032
telemt_me_endpoint_quarantine_total 1018
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1224
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
telemt_me_writers_active_current 80
telemt_desync_total 37203
telemt_desync_full_logged_total 12516
telemt_desync_suppressed_total 24687
telemt_desync_frames_bucket_total{bucket="1_2"} 9148
telemt_desync_frames_bucket_total{bucket="3_10"} 14328
telemt_desync_frames_bucket_total{bucket="gt_10"} 13727
telemt_pool_swap_total 171
telemt_pool_force_close_total 5320
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 51589
telemt_me_writer_removed_unexpected_total 1575
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4774
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48232
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 478
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46269
telemt_me_writer_teardown_success_total{mode="normal"} 53006
telemt_me_writer_teardown_noop_total 51612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104618
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 100.949733
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104618
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 1427
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8298606
telemt_user_connections_current{user="hello"} 1583
telemt_user_octets_from_client{user="hello"} 207551889989 (193.30 GB)
telemt_user_octets_to_client{user="hello"} 3741020137030 (3.40 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 161953.6 (44h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10578248
telemt_connections_bad_total 912557
telemt_connections_current 1419
telemt_connections_me_current 1419
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 338584
telemt_upstream_connect_attempt_total 70297
telemt_upstream_connect_success_total 69306
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 69488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2094
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4782
telemt_me_reconnect_success_total 1928
telemt_me_reader_eof_total 1680
telemt_me_idle_close_by_peer_total 1679
telemt_me_route_drop_no_conn_total 5170653
telemt_me_route_drop_channel_closed_total 368
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7982441
telemt_me_endpoint_quarantine_total 1100
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1190
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36686
telemt_desync_full_logged_total 12140
telemt_desync_suppressed_total 24546
telemt_desync_frames_bucket_total{bucket="1_2"} 9280
telemt_desync_frames_bucket_total{bucket="3_10"} 14036
telemt_desync_frames_bucket_total{bucket="gt_10"} 13370
telemt_pool_swap_total 169
telemt_pool_force_close_total 5266
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 51937
telemt_me_writer_removed_unexpected_total 1822
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5198
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48474
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4724
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46671
telemt_me_writer_teardown_success_total{mode="normal"} 53672
telemt_me_writer_teardown_noop_total 52008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105680
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.887117
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105680
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1667
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 7975249
telemt_user_connections_current{user="hello"} 1419
telemt_user_octets_from_client{user="hello"} 184448645129 (171.78 GB)
telemt_user_octets_to_client{user="hello"} 3318675098145 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 32233.2 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10384053
telemt_connections_bad_total 635491
telemt_connections_current 2301
telemt_connections_me_current 2301
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 202334
telemt_upstream_connect_attempt_total 41296
telemt_upstream_connect_success_total 39209
telemt_upstream_connect_fail_total 1480
telemt_upstream_connect_attempts_per_request{bucket="1"} 40689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5915
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1480
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6142
telemt_me_reconnect_success_total 786
telemt_me_reader_eof_total 488
telemt_me_idle_close_by_peer_total 488
telemt_me_route_drop_no_conn_total 25028329
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8633035
telemt_me_endpoint_quarantine_total 203
telemt_me_single_endpoint_outage_enter_total 59
telemt_me_single_endpoint_outage_exit_total 59
telemt_me_single_endpoint_outage_reconnect_attempt_total 110
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 110
telemt_me_single_endpoint_shadow_rotate_total 253
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 13700
telemt_desync_full_logged_total 3561
telemt_desync_suppressed_total 10139
telemt_desync_frames_bucket_total{bucket="1_2"} 2529
telemt_desync_frames_bucket_total{bucket="3_10"} 5549
telemt_desync_frames_bucket_total{bucket="gt_10"} 5622
telemt_pool_swap_total 31
telemt_pool_force_close_total 1186
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 9014
telemt_me_writer_removed_unexpected_total 691
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1430
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8237
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7828
telemt_me_writer_teardown_success_total{mode="normal"} 9667
telemt_me_writer_teardown_noop_total 9019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18686
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.894236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18686
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 296
telemt_me_writer_restored_same_endpoint_total 526
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 8654761
telemt_user_connections_current{user="hello"} 2301
telemt_user_octets_from_client{user="hello"} 71562183391 (66.65 GB)
telemt_user_octets_to_client{user="hello"} 363639649661 (338.67 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 161959.7 (44h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10396947
telemt_connections_bad_total 874530
telemt_connections_current 1919
telemt_connections_me_current 1919
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 230787
telemt_upstream_connect_attempt_total 99035
telemt_upstream_connect_success_total 98010
telemt_upstream_connect_fail_total 870
telemt_upstream_connect_attempts_per_request{bucket="1"} 98880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 870
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72095
telemt_me_reconnect_success_total 2668
telemt_me_reader_eof_total 2370
telemt_me_idle_close_by_peer_total 2368
telemt_me_route_drop_no_conn_total 5107038
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8202759
telemt_me_endpoint_quarantine_total 1085
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1205
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 43082
telemt_desync_full_logged_total 14707
telemt_desync_suppressed_total 28375
telemt_desync_frames_bucket_total{bucket="1_2"} 8773
telemt_desync_frames_bucket_total{bucket="3_10"} 16623
telemt_desync_frames_bucket_total{bucket="gt_10"} 17686
telemt_pool_swap_total 165
telemt_pool_force_close_total 4907
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 616
telemt_me_draining_writers_reap_progress_total 55060
telemt_me_writer_removed_unexpected_total 2411
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5883
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51611
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4221
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 686
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50153
telemt_me_writer_teardown_success_total{mode="normal"} 57494
telemt_me_writer_teardown_noop_total 55061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112555
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.596558
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112555
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 616
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2236
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8206489
telemt_user_connections_current{user="hello"} 1919
telemt_user_octets_from_client{user="hello"} 186540323509 (173.73 GB)
telemt_user_octets_to_client{user="hello"} 3098340895416 (2.82 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 729
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 98795.6 (27h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10861727
telemt_connections_bad_total 414459
telemt_connections_current 1752
telemt_connections_me_current 1752
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4528350
telemt_upstream_connect_attempt_total 47212
telemt_upstream_connect_success_total 46862
telemt_upstream_connect_fail_total 341
telemt_upstream_connect_attempts_per_request{bucket="1"} 47203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 341
telemt_me_reconnect_attempts_total 48217
telemt_me_reconnect_success_total 1561
telemt_me_reader_eof_total 1220
telemt_me_idle_close_by_peer_total 1219
telemt_me_route_drop_no_conn_total 3959160
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5217594
telemt_me_endpoint_quarantine_total 639
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 742
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 28978
telemt_desync_full_logged_total 9823
telemt_desync_suppressed_total 19155
telemt_desync_frames_bucket_total{bucket="1_2"} 5840
telemt_desync_frames_bucket_total{bucket="3_10"} 11438
telemt_desync_frames_bucket_total{bucket="gt_10"} 11700
telemt_pool_swap_total 104
telemt_pool_force_close_total 3194
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 332
telemt_me_draining_writers_reap_progress_total 34027
telemt_me_writer_removed_unexpected_total 1281
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3044
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32296
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2773
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 421
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30833
telemt_me_writer_teardown_success_total{mode="normal"} 35340
telemt_me_writer_teardown_noop_total 34034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69374
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.082816
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69374
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 332
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1387
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5210867
telemt_user_connections_current{user="hello"} 1752
telemt_user_octets_from_client{user="hello"} 112667545156 (104.93 GB)
telemt_user_octets_to_client{user="hello"} 1979793666238 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 79766.9 (22h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1120677
telemt_connections_bad_total 18090
telemt_connections_current 1132
telemt_connections_me_current 1132
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20955
telemt_upstream_connect_attempt_total 38645
telemt_upstream_connect_success_total 38534
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 38621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 599
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_reconnect_attempts_total 1749
telemt_me_reconnect_success_total 742
telemt_me_reader_eof_total 717
telemt_me_idle_close_by_peer_total 717
telemt_me_route_drop_no_conn_total 392108
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 997346
telemt_me_endpoint_quarantine_total 676
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 658
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
telemt_desync_total 5732
telemt_desync_full_logged_total 1747
telemt_desync_suppressed_total 3985
telemt_desync_frames_bucket_total{bucket="1_2"} 1359
telemt_desync_frames_bucket_total{bucket="3_10"} 2254
telemt_desync_frames_bucket_total{bucket="gt_10"} 2119
telemt_pool_swap_total 85
telemt_pool_force_close_total 2178
telemt_me_writer_close_signal_drop_total 125
telemt_me_draining_writers_reap_progress_total 32045
telemt_me_writer_removed_unexpected_total 692
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2481
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30283
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2095
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29867
telemt_me_writer_teardown_success_total{mode="normal"} 32764
telemt_me_writer_teardown_noop_total 32048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64812
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.830304
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64812
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 125
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 993753
telemt_user_connections_current{user="hello"} 1132
telemt_user_octets_from_client{user="hello"} 18351824021 (17.09 GB)
telemt_user_octets_to_client{user="hello"} 428570353611 (399.14 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 161964.0 (44h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12679954
telemt_connections_bad_total 1470160
telemt_connections_current 1754
telemt_connections_me_current 1754
telemt_handshake_timeouts_total 354868
telemt_upstream_connect_attempt_total 60924
telemt_upstream_connect_success_total 60632
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 60820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_reconnect_attempts_total 2384
telemt_me_reconnect_success_total 1264
telemt_me_reader_eof_total 1227
telemt_me_idle_close_by_peer_total 1227
telemt_me_route_drop_no_conn_total 4246741
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9592497
telemt_me_endpoint_quarantine_total 1083
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1208
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 39426
telemt_desync_full_logged_total 12864
telemt_desync_suppressed_total 26562
telemt_desync_frames_bucket_total{bucket="1_2"} 9396
telemt_desync_frames_bucket_total{bucket="3_10"} 14583
telemt_desync_frames_bucket_total{bucket="gt_10"} 15447
telemt_pool_swap_total 179
telemt_pool_force_close_total 4937
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 632
telemt_me_draining_writers_reap_progress_total 54818
telemt_me_writer_removed_unexpected_total 1179
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4506
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51525
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4763
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49881
telemt_me_writer_teardown_success_total{mode="normal"} 56031
telemt_me_writer_teardown_noop_total 54820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110851
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.509896
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110851
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 632
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1104
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 9561598
telemt_user_connections_current{user="hello"} 1754
telemt_user_octets_from_client{user="hello"} 187420231164 (174.55 GB)
telemt_user_octets_to_client{user="hello"} 4222763367260 (3.84 TB)
telemt_user_unique_ips_current{user="hello"} 647
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 161961.1 (44h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10998072
telemt_connections_bad_total 1229157
telemt_connections_current 1685
telemt_connections_me_current 1685
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 285495
telemt_upstream_connect_attempt_total 86933
telemt_upstream_connect_success_total 86198
telemt_upstream_connect_fail_total 575
telemt_upstream_connect_attempts_per_request{bucket="1"} 86773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2049
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 575
telemt_me_reconnect_attempts_total 9141
telemt_me_reconnect_success_total 2163
telemt_me_reader_eof_total 2018
telemt_me_idle_close_by_peer_total 2018
telemt_me_seq_mismatch_total 76
telemt_me_route_drop_no_conn_total 5489226
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8508070
telemt_me_endpoint_quarantine_total 1223
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1210
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_me_writers_active_current 92
telemt_desync_total 38746
telemt_desync_full_logged_total 12515
telemt_desync_suppressed_total 26231
telemt_desync_frames_bucket_total{bucket="1_2"} 9638
telemt_desync_frames_bucket_total{bucket="3_10"} 14429
telemt_desync_frames_bucket_total{bucket="gt_10"} 14679
telemt_pool_swap_total 170
telemt_pool_force_close_total 4752
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 54369
telemt_me_writer_removed_unexpected_total 2044
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5675
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50808
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4313
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49617
telemt_me_writer_teardown_success_total{mode="normal"} 56483
telemt_me_writer_teardown_noop_total 54374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110857
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.719301
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110857
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1761
telemt_me_writer_restored_fallback_total 102
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 8513985
telemt_user_connections_current{user="hello"} 1685
telemt_user_octets_from_client{user="hello"} 149644599225 (139.37 GB)
telemt_user_octets_to_client{user="hello"} 3261842870491 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 232
```