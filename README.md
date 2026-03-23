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

# Server Metrics 2026-03-23 00:15:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 97716.9 (27h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3446769
telemt_connections_bad_total 293321
telemt_connections_current 841
telemt_connections_me_current 841
telemt_handshake_timeouts_total 107971
telemt_upstream_connect_attempt_total 36158
telemt_upstream_connect_success_total 36157
telemt_upstream_connect_attempts_per_request{bucket="1"} 36157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1373
telemt_me_reconnect_success_total 581
telemt_me_reader_eof_total 597
telemt_me_idle_close_by_peer_total 597
telemt_me_route_drop_no_conn_total 2975713
telemt_me_route_drop_channel_closed_total 1231
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2858063
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
telemt_desync_total 12301
telemt_desync_full_logged_total 3851
telemt_desync_suppressed_total 8450
telemt_desync_frames_bucket_total{bucket="1_2"} 3322
telemt_desync_frames_bucket_total{bucket="3_10"} 4475
telemt_desync_frames_bucket_total{bucket="gt_10"} 4504
telemt_pool_swap_total 108
telemt_pool_force_close_total 3352
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 647
telemt_me_draining_writers_reap_progress_total 33116
telemt_me_writer_removed_unexpected_total 576
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2401
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30938
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3296
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29764
telemt_me_writer_teardown_success_total{mode="normal"} 33339
telemt_me_writer_teardown_noop_total 33127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66466
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 375.995607
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66466
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 647
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 519
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2847282
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 40780326200 (37.98 GB)
telemt_user_octets_to_client{user="hello"} 779004156828 (725.50 GB)
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 111083.4 (30h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3982034
telemt_connections_bad_total 363557
telemt_connections_current 181
telemt_connections_me_current 181
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100363
telemt_upstream_connect_attempt_total 68675
telemt_upstream_connect_success_total 67849
telemt_upstream_connect_fail_total 733
telemt_upstream_connect_attempts_per_request{bucket="1"} 68582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 733
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9807
telemt_me_reconnect_success_total 3551
telemt_me_reader_eof_total 3557
telemt_me_idle_close_by_peer_total 3557
telemt_me_route_drop_no_conn_total 3639285
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3166627
telemt_me_endpoint_quarantine_total 858
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 864
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 12919
telemt_desync_full_logged_total 7240
telemt_desync_suppressed_total 5679
telemt_desync_frames_bucket_total{bucket="1_2"} 2934
telemt_desync_frames_bucket_total{bucket="3_10"} 5064
telemt_desync_frames_bucket_total{bucket="gt_10"} 4921
telemt_pool_swap_total 103
telemt_pool_force_close_total 3031
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 246
telemt_me_draining_writers_reap_progress_total 45272
telemt_me_writer_removed_unexpected_total 3489
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6047
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42745
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42241
telemt_me_writer_teardown_success_total{mode="normal"} 48792
telemt_me_writer_teardown_noop_total 45273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94065
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.566616
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94065
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 246
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 3189
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 3179108
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 42919603006 (39.97 GB)
telemt_user_octets_to_client{user="hello"} 788599568008 (734.44 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 185943.2 (51h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16298882
telemt_connections_bad_total 1641536
telemt_connections_current 766
telemt_connections_me_current 766
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396854
telemt_upstream_connect_attempt_total 83030
telemt_upstream_connect_success_total 82927
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 82944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1711
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2973
telemt_me_reconnect_success_total 1551
telemt_me_reader_eof_total 1498
telemt_me_idle_close_by_peer_total 1496
telemt_me_route_drop_no_conn_total 14040923
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12946895
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
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 53647
telemt_desync_full_logged_total 17016
telemt_desync_suppressed_total 36631
telemt_desync_frames_bucket_total{bucket="1_2"} 11945
telemt_desync_frames_bucket_total{bucket="3_10"} 20921
telemt_desync_frames_bucket_total{bucket="gt_10"} 20781
telemt_pool_swap_total 201
telemt_pool_force_close_total 6644
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1056
telemt_me_draining_writers_reap_progress_total 62587
telemt_me_writer_removed_unexpected_total 1443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57922
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6174
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55943
telemt_me_writer_teardown_success_total{mode="normal"} 63304
telemt_me_writer_teardown_noop_total 62640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125944
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.549742
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125944
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1056
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1342
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 12946955
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 190897571041 (177.79 GB)
telemt_user_octets_to_client{user="hello"} 3482678687387 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 185944.6 (51h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11838145
telemt_connections_bad_total 1225209
telemt_connections_current 575
telemt_connections_me_current 575
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344406
telemt_upstream_connect_attempt_total 97403
telemt_upstream_connect_success_total 96084
telemt_upstream_connect_fail_total 866
telemt_upstream_connect_attempts_per_request{bucket="1"} 96950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3799
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 866
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4385
telemt_me_reconnect_success_total 1853
telemt_me_reader_eof_total 1718
telemt_me_idle_close_by_peer_total 1718
telemt_me_route_drop_no_conn_total 4551511
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8793385
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
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 38687
telemt_desync_full_logged_total 13021
telemt_desync_suppressed_total 25666
telemt_desync_frames_bucket_total{bucket="1_2"} 9580
telemt_desync_frames_bucket_total{bucket="3_10"} 14860
telemt_desync_frames_bucket_total{bucket="gt_10"} 14247
telemt_pool_swap_total 198
telemt_pool_force_close_total 6001
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 60835
telemt_me_writer_removed_unexpected_total 1749
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5485
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56954
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54834
telemt_me_writer_teardown_success_total{mode="normal"} 62439
telemt_me_writer_teardown_noop_total 60860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123299
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.383130
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123299
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 1583
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 8731157
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 217655838888 (202.71 GB)
telemt_user_octets_to_client{user="hello"} 3952419062419 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 185908.7 (51h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11027664
telemt_connections_bad_total 969356
telemt_connections_current 504
telemt_connections_me_current 504
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345402
telemt_upstream_connect_attempt_total 81665
telemt_upstream_connect_success_total 80107
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 80312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38773
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5697
telemt_me_reconnect_success_total 2340
telemt_me_reader_eof_total 2082
telemt_me_idle_close_by_peer_total 2081
telemt_me_route_drop_no_conn_total 5333466
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8338493
telemt_me_endpoint_quarantine_total 1302
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1373
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
telemt_me_writers_active_current 43
telemt_desync_total 37997
telemt_desync_full_logged_total 12597
telemt_desync_suppressed_total 25400
telemt_desync_frames_bucket_total{bucket="1_2"} 9600
telemt_desync_frames_bucket_total{bucket="3_10"} 14528
telemt_desync_frames_bucket_total{bucket="gt_10"} 13869
telemt_pool_swap_total 194
telemt_pool_force_close_total 5902
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 737
telemt_me_draining_writers_reap_progress_total 61202
telemt_me_writer_removed_unexpected_total 2234
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6235
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57131
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5331
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55300
telemt_me_writer_teardown_success_total{mode="normal"} 63366
telemt_me_writer_teardown_noop_total 61273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124639
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.678338
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124639
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 737
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2031
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8330464
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 192542830063 (179.32 GB)
telemt_user_octets_to_client{user="hello"} 3462789506469 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 56188.8 (15h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11190125
telemt_connections_bad_total 668486
telemt_connections_current 952
telemt_connections_me_current 952
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 265450
telemt_upstream_connect_attempt_total 55643
telemt_upstream_connect_success_total 52790
telemt_upstream_connect_fail_total 1903
telemt_upstream_connect_attempts_per_request{bucket="1"} 54693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6005
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1903
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7467
telemt_me_reconnect_success_total 1162
telemt_me_reader_eof_total 738
telemt_me_idle_close_by_peer_total 737
telemt_me_route_drop_no_conn_total 25279638
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9293897
telemt_me_endpoint_quarantine_total 412
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 444
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
telemt_desync_total 16259
telemt_desync_full_logged_total 4412
telemt_desync_suppressed_total 11847
telemt_desync_frames_bucket_total{bucket="1_2"} 3086
telemt_desync_frames_bucket_total{bucket="3_10"} 6607
telemt_desync_frames_bucket_total{bucket="gt_10"} 6566
telemt_pool_swap_total 58
telemt_pool_force_close_total 1936
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 474
telemt_me_draining_writers_reap_progress_total 17276
telemt_me_writer_removed_unexpected_total 1053
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2368
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15903
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1629
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15340
telemt_me_writer_teardown_success_total{mode="normal"} 18271
telemt_me_writer_teardown_noop_total 17295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35566
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.562654
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35566
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 474
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 759
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 9319348
telemt_user_connections_current{user="hello"} 952
telemt_user_octets_from_client{user="hello"} 86667511982 (80.72 GB)
telemt_user_octets_to_client{user="hello"} 598612282237 (557.50 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 185915.4 (51h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10962183
telemt_connections_bad_total 942383
telemt_connections_current 766
telemt_connections_me_current 766
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241754
telemt_upstream_connect_attempt_total 110548
telemt_upstream_connect_success_total 109411
telemt_upstream_connect_fail_total 965
telemt_upstream_connect_attempts_per_request{bucket="1"} 110376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 965
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72823
telemt_me_reconnect_success_total 3031
telemt_me_reader_eof_total 2723
telemt_me_idle_close_by_peer_total 2721
telemt_me_route_drop_no_conn_total 5256645
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8651917
telemt_me_endpoint_quarantine_total 1240
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1403
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
telemt_me_writers_active_current 44
telemt_desync_total 46131
telemt_desync_full_logged_total 15790
telemt_desync_suppressed_total 30341
telemt_desync_frames_bucket_total{bucket="1_2"} 9372
telemt_desync_frames_bucket_total{bucket="3_10"} 17655
telemt_desync_frames_bucket_total{bucket="gt_10"} 19104
telemt_pool_swap_total 190
telemt_pool_force_close_total 5606
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 65365
telemt_me_writer_removed_unexpected_total 2754
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6735
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61417
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59759
telemt_me_writer_teardown_success_total{mode="normal"} 68152
telemt_me_writer_teardown_noop_total 65366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.219767
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2562
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8654953
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 194353784977 (181.01 GB)
telemt_user_octets_to_client{user="hello"} 3304541532920 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 122751.6 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11658266
telemt_connections_bad_total 476436
telemt_connections_current 456
telemt_connections_me_current 456
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4759390
telemt_upstream_connect_attempt_total 58712
telemt_upstream_connect_success_total 58284
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 58701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_reconnect_attempts_total 48851
telemt_me_reconnect_success_total 1781
telemt_me_reader_eof_total 1452
telemt_me_idle_close_by_peer_total 1451
telemt_me_route_drop_no_conn_total 4083105
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5601097
telemt_me_endpoint_quarantine_total 828
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 939
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
telemt_me_writers_active_current 47
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
telemt_me_draining_writers_reap_progress_total 44439
telemt_me_writer_removed_unexpected_total 1503
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3705
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42280
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3401
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40597
telemt_me_writer_teardown_success_total{mode="normal"} 45985
telemt_me_writer_teardown_noop_total 44446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90431
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.677925
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90431
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2735
telemt_me_writer_restored_same_endpoint_total 1582
telemt_me_writer_restored_fallback_total 23
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5593670
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 118946687148 (110.78 GB)
telemt_user_octets_to_client{user="hello"} 2164539945470 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 103722.4 (28h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1503791
telemt_connections_bad_total 36679
telemt_connections_current 391
telemt_connections_me_current 391
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30113
telemt_upstream_connect_attempt_total 48591
telemt_upstream_connect_success_total 48436
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 48563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 783
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2203
telemt_me_reconnect_success_total 888
telemt_me_reader_eof_total 872
telemt_me_idle_close_by_peer_total 872
telemt_me_route_drop_no_conn_total 514752
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1336004
telemt_me_endpoint_quarantine_total 845
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 855
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
telemt_me_writers_active_current 41
telemt_desync_total 8698
telemt_desync_full_logged_total 2574
telemt_desync_suppressed_total 6124
telemt_desync_frames_bucket_total{bucket="1_2"} 2352
telemt_desync_frames_bucket_total{bucket="3_10"} 3337
telemt_desync_frames_bucket_total{bucket="gt_10"} 3009
telemt_pool_swap_total 112
telemt_pool_force_close_total 2892
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 161
telemt_me_draining_writers_reap_progress_total 40978
telemt_me_writer_removed_unexpected_total 842
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3181
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38676
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2804
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38086
telemt_me_writer_teardown_success_total{mode="normal"} 41857
telemt_me_writer_teardown_noop_total 40982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82839
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.192777
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82839
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 161
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1331829
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 25814195821 (24.04 GB)
telemt_user_octets_to_client{user="hello"} 571365622459 (532.13 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 185919.9 (51h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13297932
telemt_connections_bad_total 1596906
telemt_connections_current 633
telemt_connections_me_current 633
telemt_handshake_timeouts_total 387377
telemt_upstream_connect_attempt_total 72474
telemt_upstream_connect_success_total 72128
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 72338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2918
telemt_me_reconnect_success_total 1452
telemt_me_reader_eof_total 1438
telemt_me_idle_close_by_peer_total 1438
telemt_me_route_drop_no_conn_total 4479709
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10028201
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
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 41947
telemt_desync_full_logged_total 13697
telemt_desync_suppressed_total 28250
telemt_desync_frames_bucket_total{bucket="1_2"} 10118
telemt_desync_frames_bucket_total{bucket="3_10"} 15422
telemt_desync_frames_bucket_total{bucket="gt_10"} 16407
telemt_pool_swap_total 206
telemt_pool_force_close_total 5536
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 674
telemt_me_draining_writers_reap_progress_total 65452
telemt_me_writer_removed_unexpected_total 1376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5193
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61687
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59916
telemt_me_writer_teardown_success_total{mode="normal"} 66880
telemt_me_writer_teardown_noop_total 65454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132334
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.743984
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132334
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 674
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1274
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 9994930
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 194465613316 (181.11 GB)
telemt_user_octets_to_client{user="hello"} 4432990872460 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 185916.5 (51h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11596969
telemt_connections_bad_total 1341961
telemt_connections_current 498
telemt_connections_me_current 498
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 310148
telemt_upstream_connect_attempt_total 99172
telemt_upstream_connect_success_total 98292
telemt_upstream_connect_fail_total 671
telemt_upstream_connect_attempts_per_request{bucket="1"} 98963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 671
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10329
telemt_me_reconnect_success_total 2542
telemt_me_reader_eof_total 2358
telemt_me_idle_close_by_peer_total 2357
telemt_me_seq_mismatch_total 95
telemt_me_route_drop_no_conn_total 5640498
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8935026
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
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 41697
telemt_desync_full_logged_total 13406
telemt_desync_suppressed_total 28291
telemt_desync_frames_bucket_total{bucket="1_2"} 10748
telemt_desync_frames_bucket_total{bucket="3_10"} 15329
telemt_desync_frames_bucket_total{bucket="gt_10"} 15620
telemt_pool_swap_total 196
telemt_pool_force_close_total 5329
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 661
telemt_me_draining_writers_reap_progress_total 65469
telemt_me_writer_removed_unexpected_total 2399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6555
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61396
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4858
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60140
telemt_me_writer_teardown_success_total{mode="normal"} 67951
telemt_me_writer_teardown_noop_total 65474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133425
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.442885
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133425
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 661
telemt_me_refill_failed_total 403
telemt_me_writer_restored_same_endpoint_total 2051
telemt_me_writer_restored_fallback_total 130
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 8940356
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 157167761585 (146.37 GB)
telemt_user_octets_to_client{user="hello"} 3478753978951 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 53
```